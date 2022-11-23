<script>
  import BreadcrumbExample from "$lib/content/BreadcrumbExample.svelte";

</script>
<div class="grid-sidenav3col">
  <div class="grid-item-breadcrumbs breadcrumbs-area">
    <BreadcrumbExample />
  </div>
  <div class="grid-item-leftnav leftsidebar-area">
        Side nav goes here
  </div>
  <div class="grid-item-content content-area">
    <auro-header>3 Column Page Layout</auro-header>
    <p>This is an example where we would use a specific grid just for situations where we need a side nav.  The code for this is very simple.  We can adjust the breakpoints as needed.</p>
    <p>For this scenario the side nav has a fixed width of 330px on breakpoints 768px and above, while the content on the right will scale to fit the screen.</p>
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sint ipsum repellendus tenetur eligendi? Ut magni cumque exercitationem accusamus error quo maxime molestiae rerum fuga repellendus! Culpa temporibus rerum doloremque dolore libero quaerat natus atque nemo excepturi, alias necessitatibus quibusdam tempore qui dolores cum corrupti tenetur ad itaque architecto. Tempore ratione quasi ad quos suscipit dolores rem blanditiis adipisci vitae quae, harum vero. Saepe, excepturi recusandae sit minima cupiditate eaque quia fugiat in? Debitis, rerum similique doloribus non voluptatibus esse dolorem nobis soluta incidunt eligendi, quis reprehenderit dicta iure vitae provident enim vero earum. Autem veritatis cumque obcaecati dicta voluptatibus iusto eveniet deleniti. Quae nam voluptatem et optio nulla porro cum, soluta explicabo recusandae officiis quaerat dignissimos accusantium, a voluptates. Vero quibusdam cupiditate quasi ex! In ipsa vitae est non, provident praesentium fugiat quod, animi, asperiores harum corrupti natus laborum excepturi iure eveniet! Quod iure quas perferendis nostrum, doloribus iusto cupiditate. Amet quo recusandae exercitationem mollitia dolores commodi qui voluptatibus reprehenderit libero est optio, iusto eligendi corrupti doloremque ipsam ad unde quis magni numquam fugit maxime explicabo rem error! Cupiditate, neque accusamus deleniti harum reprehenderit ratione modi labore. Distinctio eligendi magni, ab, necessitatibus totam modi a, accusamus ipsum voluptas beatae adipisci.</p>
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sint ipsum repellendus tenetur eligendi? Ut magni cumque exercitationem accusamus error quo maxime molestiae rerum fuga repellendus! Culpa temporibus rerum doloremque dolore libero quaerat natus atque nemo excepturi, alias necessitatibus quibusdam tempore qui dolores cum corrupti tenetur ad itaque architecto. Tempore ratione quasi ad quos suscipit dolores rem blanditiis adipisci vitae quae, harum vero. Saepe, excepturi recusandae sit minima cupiditate eaque quia fugiat in? Debitis, rerum similique doloribus non voluptatibus esse dolorem nobis soluta incidunt eligendi, quis reprehenderit dicta iure vitae provident enim vero earum. Autem veritatis cumque obcaecati dicta voluptatibus iusto eveniet deleniti. Quae nam voluptatem et optio nulla porro cum, soluta explicabo recusandae officiis quaerat dignissimos accusantium, a voluptates. Vero quibusdam cupiditate quasi ex! In ipsa vitae est non, provident praesentium fugiat quod, animi, asperiores harum corrupti natus laborum excepturi iure eveniet! Quod iure quas perferendis nostrum, doloribus iusto cupiditate. Amet quo recusandae exercitationem mollitia dolores commodi qui voluptatibus reprehenderit libero est optio, iusto eligendi corrupti doloremque ipsam ad unde quis magni numquam fugit maxime explicabo rem error! Cupiditate, neque accusamus deleniti harum reprehenderit ratione modi labore. Distinctio eligendi magni, ab, necessitatibus totam modi a, accusamus ipsum voluptas beatae adipisci.</p>
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sint ipsum repellendus tenetur eligendi? Ut magni cumque exercitationem accusamus error quo maxime molestiae rerum fuga repellendus! Culpa temporibus rerum doloremque dolore libero quaerat natus atque nemo excepturi, alias necessitatibus quibusdam tempore qui dolores cum corrupti tenetur ad itaque architecto. Tempore ratione quasi ad quos suscipit dolores rem blanditiis adipisci vitae quae, harum vero. Saepe, excepturi recusandae sit minima cupiditate eaque quia fugiat in? Debitis, rerum similique doloribus non voluptatibus esse dolorem nobis soluta incidunt eligendi, quis reprehenderit dicta iure vitae provident enim vero earum. Autem veritatis cumque obcaecati dicta voluptatibus iusto eveniet deleniti. Quae nam voluptatem et optio nulla porro cum, soluta explicabo recusandae officiis quaerat dignissimos accusantium, a voluptates. Vero quibusdam cupiditate quasi ex! In ipsa vitae est non, provident praesentium fugiat quod, animi, asperiores harum corrupti natus laborum excepturi iure eveniet! Quod iure quas perferendis nostrum, doloribus iusto cupiditate. Amet quo recusandae exercitationem mollitia dolores commodi qui voluptatibus reprehenderit libero est optio, iusto eligendi corrupti doloremque ipsam ad unde quis magni numquam fugit maxime explicabo rem error! Cupiditate, neque accusamus deleniti harum reprehenderit ratione modi labore. Distinctio eligendi magni, ab, necessitatibus totam modi a, accusamus ipsum voluptas beatae adipisci.</p>
  </div>
  <div class="grid-item-rightnav rightsidebar-area">
    Anchor nav goes here
</div>
</div>



<style>
  @import "../../globalGrid.css";
  @import "../../globalGridExamples.css";
  .grid-item-leftnav {
    background: var(--auro-color-brand-neutral-200);
    padding: 1.5rem;
    margin: -1.5rem -1.5rem 1rem;
  }
  @media screen and (min-width: 768px) { 
    .grid-item-leftnav {
    margin: unset;
    }
  }
  .grid-item-rightnav {
    background: var(--auro-color-brand-neutral-100);
    padding: 1.5rem;
  }
  @media screen and (min-width: 768px) { 
    .grid-item-rightnav {
    margin: unset;
    }
  }
</style>
