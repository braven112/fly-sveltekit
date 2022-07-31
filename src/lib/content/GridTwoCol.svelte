<auro-header level="3" margin="top" size="none" display="500">2 Column Layout - Auto</auro-header>
<p>By default the grid item's will resize as needed.</p>
<div class="grid">
  <div class="grid-item">
    <div class="avatar-details">
        <auro-avatar md code="AUS"></auro-avatar>
        <div class="avatar-cityname">Austin, TX</div>
        <div class="avatar-airport fineprint">Austin/Bergstrom Intl.</div>
        <div class="avatar-airport fineprint">AUS</div>
    </div>
  </div>
  <div class="grid-item">
    <div class="avatar-details">
        <auro-avatar md code="SBP"></auro-avatar>
        <div class="avatar-cityname">San Luis Obispo, CA</div>
        <div class="avatar-airport fineprint">San Luis Obispo</div>
        <div class="avatar-airport fineprint">SBP</div>
    </div>
  </div>
</div>
<auro-header level="3" margin="top" size="none" display="500">2 Column Layout - Define columns per beakpoint</auro-header>
<p>We can also explicitly set the layout at different breakpoints</p>
<div class="grid">
  <div class="col-12 col-xs-6 grid-item">
    <div class="avatar-details">
        <auro-avatar md code="AUS"></auro-avatar>
        <div class="avatar-cityname">Austin, TX</div>
        <div class="avatar-airport fineprint">Austin/Bergstrom Intl.</div>
        <div class="avatar-airport fineprint">AUS</div>
    </div>
  </div>
  <div class="col-12 col-xs-6 grid-item">
    <div class="avatar-details">
        <auro-avatar md code="SBP"></auro-avatar>
        <div class="avatar-cityname">San Luis Obispo, CA</div>
        <div class="avatar-airport fineprint">San Luis Obispo</div>
        <div class="avatar-airport fineprint">SBP</div>
    </div>
  </div>
</div>

<auro-header level="3" margin="top" size="none" display="500">2 Column Layout - Scroll</auro-header>
<p>We can also set it to scroll on mobile</p>
<div class="grid grid-scroll-2">
  <div class="grid-item">
    <div class="avatar-details">
        <auro-avatar md code="AUS"></auro-avatar>
        <div class="avatar-cityname">Austin, TX</div>
        <div class="avatar-airport fineprint">Austin/Bergstrom Intl.</div>
        <div class="avatar-airport fineprint">AUS</div>
    </div>
  </div>
  <div class="grid-item">
    <div class="avatar-details">
        <auro-avatar md code="SBP"></auro-avatar>
        <div class="avatar-cityname">San Luis Obispo, CA</div>
        <div class="avatar-airport fineprint">San Luis Obispo</div>
        <div class="avatar-airport fineprint">SBP</div>
    </div>
  </div>
</div>

<style>
  @import "../../globalGrid.css";
  @import "../../globalGridExamples.css";
.grid {
  margin-bottom: 1rem;
}
</style>
