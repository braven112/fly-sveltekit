<auro-header level="3" margin="top" size="none" display="500">Default form inputs - No properties used in this example</auro-header>
<div class="grid grid--scroll-3">
  <div class="grid-item">
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
  </div>

  <div class="grid-item">
    <auro-select>
      <auro-menu noCheckmark >
        <auro-menuoption value="stops">Stops</auro-menuoption>
        <auro-menuoption value="price">Price</auro-menuoption>
        <auro-menuoption value="duration">Duration</auro-menuoption>
        <auro-menuoption value="departure">Departure</auro-menuoption>
        <auro-menuoption value="arrival">Arrival</auro-menuoption>
        <auro-menuoption value="prefer alaska">Prefer Alaska</auro-menuoption>
      </auro-menu>
    </auro-select>
  </div>
  <div class="grid-item">
    <auro-input bordered></auro-input>
  </div>
</div>

<auro-header level="3" margin="top" size="none" display="500">Form inputs - Label and help text is included in these examples</auro-header>
<div class="grid grid--scroll-3">
  <div class="grid-item">
    <auro-combobox>
        <span slot="label">Name</span>
      <auro-menu>
        <auro-menuoption value="Apples" id="option-0">Apples</auro-menuoption>
        <auro-menuoption value="Oranges" id="option-1">Oranges</auro-menuoption>
        <auro-menuoption value="Peaches" id="option-2">Peaches</auro-menuoption>
        <auro-menuoption value="Grapes" id="option-3">Grapes</auro-menuoption>
        <auro-menuoption value="Cherries" id="option-4">Cherries</auro-menuoption>
        <auro-menuoption static nomatch>No matching option</auro-menuoption>
      </auro-menu>
    </auro-combobox>
  </div>

  <div class="grid-item">
    <auro-select>
        <span slot="label">Please choose a preference</span>
        <span slot="helpText">Preferences are maintained for future use</span>
        <auro-menu>
          <auro-menuoption value="stops">Stops</auro-menuoption>
          <auro-menuoption value="price">Price</auro-menuoption>
          <auro-menuoption value="duration">Duration</auro-menuoption>
          <auro-menuoption value="departure">Departure</auro-menuoption>
          <auro-menuoption value="arrival">Arrival</auro-menuoption>
          <auro-menuoption value="prefer alaska">Prefer Alaska</auro-menuoption>
        </auro-menu>
      </auro-select>
  </div>
  <div class="grid-item">     
      <auro-input bordered required icon type="credit-card" id="demo14">
        <slot slot="label">Card number</slot>
        <slot slot="helptext">Valid credit card numbers must include 16 digits (15 for Amex).</slot>
      </auro-input>
  </div>
</div>

<style>
  .grid {
  margin-bottom: 1rem;
}
</style>
