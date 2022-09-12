<auro-header level="3" margin="bottom" size="none" display="500">Default form inputs</auro-header>
<auro-header level="5" margin="top" size="none" display="300">No properties used in this example</auro-header>
<div class="grid grid--scroll-3">
  <div class="form-groups">
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

  <div class="form-groups">
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
  <div class="form-groups">
    <auro-input bordered></auro-input>
  </div>
</div>

<auro-header level="3" margin="bottom" size="none" display="500">Auro Form inputs</auro-header>
<auro-header level="5" margin="top" size="none" display="300">Both label and help text</auro-header>
<div class="grid grid--scroll-3">
  <div class="form-groups">
    <auro-combobox>
        <span slot="label">This is an auro-combobox label</span>
        <span slot="helpText">This is auro-combobox help text</span>
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

  <div class="form-groups">
    <auro-select>
        <span slot="label">This is an auro-select label</span>
        <span slot="helpText">This is auro-select help text</span>
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
  <div class="form-groups">     
      <auro-input bordered>
        <span slot="label">This is an auro-input label</span>
        <span slot="helptext">This is auro-input help text</span>
      </auro-input>
  </div>
</div>
<auro-header level="3" margin="bottom" size="none" display="500">Auro Form inputs</auro-header>
<auro-header level="5" margin="top" size="none" display="300">No Labels but with help text</auro-header>
<div class="grid grid--scroll-3">
  <div class="form-groups">
    <auro-combobox>
      <span slot="helpText">This is auro-combobox help text</span>
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

  <div class="form-groups">
    <auro-select>
        <span slot="helpText">This is auro-select help text</span>
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
  <div class="form-groups">     
    <auro-input bordered>
      <span slot="helptext">This is auro-input help text</span>
    </auro-input>
  </div>
</div>

<auro-header level="3" margin="bottom" size="none" display="500">Auro Form inputs</auro-header>
<auro-header level="5" margin="top" size="none" display="300">Label but no help text</auro-header>
<div class="grid grid--scroll-3">
  <div class="form-groups">
    <auro-combobox>
        <span slot="label">This is an auro-combobox label</span>
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

  <div class="form-groups">
    <auro-select>
        <span slot="label">This is an auro-select label</span>
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
  <div class="form-groups">     
    <auro-input bordered>
      <span slot="label">This is an auro-input label</span>
    </auro-input>
  </div>
</div>

<auro-header level="3" margin="bottom" size="none" display="500">Auro Form inputs</auro-header>
<auro-header level="5" margin="top" size="none" display="300">Required boolean</auro-header>
<div class="grid grid--scroll-3">
  <div class="form-groups">
    <auro-combobox required>
        <span slot="label">This is an auro-combobox label</span>
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

  <div class="form-groups">
    <auro-select required>
        <span slot="label">This is an auro-select label</span>
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
  <div class="form-groups">     
    <auro-input required bordered>
      <span slot="label">This is an auro-input label</span>
    </auro-input>
  </div>
</div>

<auro-header level="3" margin="bottom" size="none" display="500">Auro Form inputs</auro-header>
<auro-header level="5" margin="top" size="none" display="300">Error boolean</auro-header>
<div class="grid grid--scroll-3">
  <div class="form-groups">
    <auro-combobox error>
        <span slot="label">This is an auro-combobox label</span>
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

  <div class="form-groups">
    <auro-select error>
        <span slot="label">This is an auro-select label</span>
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
  <div class="form-groups">     
    <auro-input error bordered>
      <span slot="label">This is an auro-input label</span>
    </auro-input>
  </div>
</div>

<auro-header level="3" margin="bottom" size="none" display="500">Auro Form inputs</auro-header>
<auro-header level="5" margin="top" size="none" display="300">Error and Required boolean</auro-header>
<div class="grid grid--scroll-3">
  <div class="form-groups">
    <auro-combobox error required>
        <span slot="label">This is an auro-combobox label</span>
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

  <div class="form-groups">
    <auro-select error required>
        <span slot="label">This is an auro-select label</span>
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
  <div class="form-groups">     
    <auro-input error required bordered>
      <span slot="label">This is an auro-input label</span>
    </auro-input>
  </div>
</div>

<auro-header level="3" margin="bottom" size="none" display="500">Auro Form inputs</auro-header>
<auro-header level="5" margin="top" size="none" display="300">Novalidate, Error and Required boolean</auro-header>
<div class="grid grid--scroll-3">
  <div class="form-groups">
    <auro-combobox novalidate error required>
        <span slot="label">This is an auro-combobox label</span>
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

  <div class="form-groups">
    <auro-select novalidate error required>
        <span slot="label">This is an auro-select label</span>
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
  <div class="form-groups">     
    <auro-input novalidate error required bordered>
      <span slot="label">This is an auro-input label</span>
    </auro-input>
  </div>
</div>


<auro-header level="3" margin="bottom" size="none" display="500">Auro Form inputs</auro-header>
<auro-header level="5" margin="top" size="none" display="300">These examples have error="this is overriding help text"</auro-header>
<div class="grid grid--scroll-3">
  <div class="form-groups">
    <auro-combobox novalidate error="this is overriding help text" required>
        <span slot="label">This is an auro-combobox label</span>
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

  <div class="form-groups">
    <auro-select novalidate error="this is overriding help text" required>
        <span slot="label">This is an auro-select label</span>
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
  <div class="form-groups">     
    <auro-input novalidate error="this is overriding help text" required bordered>
      <span slot="label">This is an auro-input label</span>
    </auro-input>
  </div>
</div>

<style>
  .grid {
  margin-bottom: 1rem;
}
</style>
