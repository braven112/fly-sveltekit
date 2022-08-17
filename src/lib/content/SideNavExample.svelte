<auro-header level="3" margin="top" size="none" display="500">2 Column Layout - Page Layout</auro-header>
<p>The 2 column layout is super powerful and can be used to create full page layouts where one column houses a side nav and the rest of the space allows for content to stack.</p>
<p>For this scenario do we want to use our default grid system, or should we create a custom grid for this scenerio where we set a specific size for the "side nav" container and allow the right side to scale?  In this example both columns scale to size but we can set a min size for the left column so it will always house the side nav if we want.</p>
<div class="grid-sidenav">
  <div class="grid-item">
        <div class="avatar-cityname">Sidenav goes here</div>
  </div>
  <div class="grid-item">
    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sint ipsum repellendus tenetur eligendi? Ut magni cumque exercitationem accusamus error quo maxime molestiae rerum fuga repellendus! Culpa temporibus rerum doloremque dolore libero quaerat natus atque nemo excepturi, alias necessitatibus quibusdam tempore qui dolores cum corrupti tenetur ad itaque architecto. Tempore ratione quasi ad quos suscipit dolores rem blanditiis adipisci vitae quae, harum vero. Saepe, excepturi recusandae sit minima cupiditate eaque quia fugiat in? Debitis, rerum similique doloribus non voluptatibus esse dolorem nobis soluta incidunt eligendi, quis reprehenderit dicta iure vitae provident enim vero earum. Autem veritatis cumque obcaecati dicta voluptatibus iusto eveniet deleniti. Quae nam voluptatem et optio nulla porro cum, soluta explicabo recusandae officiis quaerat dignissimos accusantium, a voluptates. Vero quibusdam cupiditate quasi ex! In ipsa vitae est non, provident praesentium fugiat quod, animi, asperiores harum corrupti natus laborum excepturi iure eveniet! Quod iure quas perferendis nostrum, doloribus iusto cupiditate. Amet quo recusandae exercitationem mollitia dolores commodi qui voluptatibus reprehenderit libero est optio, iusto eligendi corrupti doloremque ipsam ad unde quis magni numquam fugit maxime explicabo rem error! Cupiditate, neque accusamus deleniti harum reprehenderit ratione modi labore. Distinctio eligendi magni, ab, necessitatibus totam modi a, accusamus ipsum voluptas beatae adipisci.
  </div>
</div>



<style>
  @import "../../globalGrid.css";
  @import "../../globalGridExamples.css";
.grid, .grid-sidenav {
  margin-bottom: 1rem;
}
</style>
