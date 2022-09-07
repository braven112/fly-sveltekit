<auro-header level="1" margin="top" size="none" display="900">Auro Forms</auro-header>
<p>This page is intended to show all of our form elements all on one page.  This page is NOT intended to show how we should do things.  Its intended to show how they CAN be implemented.  This way we can align on fallbacks if necessary and find any potential bugs.  We'll continue to add more examples.</p>
<auro-header level="3" margin="top" size="none" display="500">These are our current `bordered` defalts for all of our form elements</auro-header>
<p>These examples have no label or placeholder declared.  Its all just the default or fall back options when no slot is used or attribute declared.</p>
<div class="grid">
  <div class="form-example">
    <auro-header level="4" margin="bottom" size="none" display="200">Auro Input</auro-header>
    <auro-input bordered></auro-input>
    <auro-header level="4" margin="bottom" size="none" display="200">Auro Select</auro-header>
    <auro-select>
      <auro-menu>
        <auro-menuoption value="stops">Stops</auro-menuoption>
        <auro-menuoption value="price">Price</auro-menuoption>
        <auro-menuoption value="duration">Duration</auro-menuoption>
        <auro-menuoption value="departure">Departure</auro-menuoption>
        <auro-menuoption value="arrival">Arrival</auro-menuoption>
        <auro-menuoption value="prefer alaska">Prefer Alaska</auro-menuoption>
      </auro-menu>
    </auro-select>
    <auro-header level="4" margin="bottom" size="none" display="200">Auro Combobox</auro-header>
    <auro-combobox>
      <auro-menu>
        <auro-menuoption value="Apples" id="option-0">Apples</auro-menuoption>
        <auro-menuoption value="Oranges" id="option-1">Oranges</auro-menuoption>
        <auro-menuoption value="Peaches" id="option-2">Peaches</auro-menuoption>
        <auro-menuoption value="Grapes" id="option-3">Grapes</auro-menuoption>
        <auro-menuoption value="Cherries" id="option-4">Cherries</auro-menuoption>
        <auro-menuoption static nomatch>No matching option</auro-menuoption>
      </auro-menu>
    </auro-combobox>
    <!--<auro-header level="4" margin="bottom" size="none" display="200">Auro Datepicker</auro-header>
     <auro-datepicker></auro-datepicker> -->
    </div>
</div>
<auro-header level="3" margin="top" size="none" display="500">These are our current defalts for all of our form elements with a background</auro-header>
<p>These examples have no label or placeholder declared.  Its all just the default or fall back options when no slot is used or attribute declared.</p>
<div class="grid">
  <div class="form-example background-color">
    <div class="avatar-details">
      <auro-header level="4" margin="bottom" size="none" display="200">Auro Input</auro-header>
      <auro-input bordered></auro-input>
      <auro-header level="4" margin="bottom" size="none" display="200">Auro Select</auro-header>
      <auro-select>
        <auro-menu>
          <auro-menuoption value="stops">Stops</auro-menuoption>
          <auro-menuoption value="price">Price</auro-menuoption>
          <auro-menuoption value="duration">Duration</auro-menuoption>
          <auro-menuoption value="departure">Departure</auro-menuoption>
          <auro-menuoption value="arrival">Arrival</auro-menuoption>
          <auro-menuoption value="prefer alaska">Prefer Alaska</auro-menuoption>
        </auro-menu>
      </auro-select>
      <auro-header level="4" margin="bottom" size="none" display="200">Auro Combobox</auro-header>
      <auro-combobox noCheckmark>
        <auro-menu>
          <auro-menuoption value="Apples" id="option-0">Apples</auro-menuoption>
          <auro-menuoption value="Oranges" id="option-1">Oranges</auro-menuoption>
          <auro-menuoption value="Peaches" id="option-2">Peaches</auro-menuoption>
          <auro-menuoption value="Grapes" id="option-3">Grapes</auro-menuoption>
          <auro-menuoption value="Cherries" id="option-4">Cherries</auro-menuoption>
          <auro-menuoption static nomatch>No matching option</auro-menuoption>
        </auro-menu>
      </auro-combobox>
      <!-- <auro-header level="4" margin="bottom" size="none" display="200">Auro Datepicker</auro-header>
      <auro-datepicker></auro-datepicker> -->
    </div>
  </div>
</div>



<style>
  .grid {
  margin-bottom: 1rem;
}
  .background-color {
    background-color: #eee;
    padding: 1rem;
  }
</style>
