
<auro-header level="3" margin="top" size="none" display="500">3 Column Layout - col-12 col-sm-4</auro-header>
<p>This row will stack on mobile</p>
<div class="grid">
  <div class="col-12 col-sm-4 grid-item">
    <div class="avatar-details">
        <auro-avatar md code="AUS"></auro-avatar>
        <div class="avatar-cityname">Austin, TX</div>
        <div class="avatar-airport fineprint">Austin/Bergstrom Intl.</div>
        <div class="avatar-airport fineprint">AUS</div>
    </div>
  </div>
  <div class="col-12 col-sm-4 grid-item">
    <div class="avatar-details">
        <auro-avatar md code="SBP"></auro-avatar>
        <div class="avatar-cityname">San Luis Obispo, CA</div>
        <div class="avatar-airport fineprint">San Luis Obispo</div>
        <div class="avatar-airport fineprint">SBP</div>
    </div>
  </div>

  <div class="col-12 col-sm-4 grid-item">
    <div class="avatar-details">
        <auro-avatar md code="SEA"></auro-avatar>
        <div class="avatar-cityname">Seattle, WA</div>
        <div class="avatar-airport fineprint">Seattle/Tacoma Intl.</div>
        <div class="avatar-airport fineprint">SEA</div>
    </div>
  </div>
</div>
<auro-header level="3" margin="top" size="none" display="500">3 Column Layout - Squish</auro-header>
<p>This row will stay on a row on mobile</p>
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

  <div class="grid-item">
    <div class="avatar-details">
        <auro-avatar md code="SEA"></auro-avatar>
        <div class="avatar-cityname">Seattle, WA</div>
        <div class="avatar-airport fineprint">Seattle/Tacoma Intl.</div>
        <div class="avatar-airport fineprint">SEA</div>
    </div>
  </div>
</div>

<auro-header level="3" margin="top" size="none" display="500">3 Column Layout - 2x1 aka (`col-6 col-xs-4`, `col-6 col-xs-4`, `col-12 col-xs-4`)</auro-header>
<p>This row will collapse to 2 column on mobile with the 3rd column taking up with full width of the second row on mobile.  The implementor can decide what column takes the whole width, either the first item or the last item.</p>
<div class="grid">
  <div class="col-6 col-xs-4 grid-item">
    <div class="avatar-details">
        <auro-avatar md code="AUS"></auro-avatar>
        <div class="avatar-cityname">Austin, TX</div>
        <div class="avatar-airport fineprint">Austin/Bergstrom Intl.</div>
        <div class="avatar-airport fineprint">AUS</div>
    </div>
  </div>
  <div class="col-6 col-xs-4 grid-item">
    <div class="avatar-details">
        <auro-avatar md code="SBP"></auro-avatar>
        <div class="avatar-cityname">San Luis Obispo, CA</div>
        <div class="avatar-airport fineprint">San Luis Obispo</div>
        <div class="avatar-airport fineprint">SBP</div>
    </div>
  </div>

  <div class="col-12 col-xs-4 grid-item">
    <div class="avatar-details">
        <auro-avatar md code="SEA"></auro-avatar>
        <div class="avatar-cityname">Seattle, WA</div>
        <div class="avatar-airport fineprint">Seattle/Tacoma Intl.</div>
        <div class="avatar-airport fineprint">SEA</div>
    </div>
  </div>
</div>

<auro-header level="3" margin="top" size="none" display="500">3 Column Layout - Scroll</auro-header>
<p>This row will scroll on mobile</p>
<div class="grid grid-scroll-3">
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

  <div class="grid-item">
    <div class="avatar-details">
        <auro-avatar md code="SEA"></auro-avatar>
        <div class="avatar-cityname">Seattle, WA</div>
        <div class="avatar-airport fineprint">Seattle/Tacoma Intl.</div>
        <div class="avatar-airport fineprint">SEA</div>
    </div>
  </div>
</div>
<style>
  @import "../../globalGridExamples.css";
  .grid {
  margin-bottom: 1rem;
}
</style>
