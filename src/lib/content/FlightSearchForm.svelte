<script>
  import CityMenuOptions from "$lib/content/CityMenuOptions.svelte";
</script>

<div class="formWrapper">
  <div class="auro-datetime">Today is <auro-datetime type="date" month="long" weekday="long" /></div>
  <auro-header level="2" margin="top" size="none" display="600">Let's go somewhere!</auro-header>
  <auro-combobox required>
    <span slot="label">From</span>
    <auro-menu>
      <CityMenuOptions />
    </auro-menu>
  </auro-combobox>
  <auro-combobox required>
    <span slot="label">To</span>
    <auro-menu>
      <CityMenuOptions />
    </auro-menu>
  </auro-combobox>
  <auro-datepicker required>
    <span slot="label">Choose a date</span>
  </auro-datepicker>
  <auro-button fluid>Search</auro-button>
</div>

<style>
  auro-input,
  auro-combobox, auro-datepicker {
    margin-bottom: var(--auro-size-md);
  }
  .formWrapper {
    background-color: var(--auro-color-background-lightest);
    display: flex;
    flex-direction: column;
  }

  @media screen and (min-width: 1024px) {
    .formWrapper {
      width: 25rem;
      min-height: 24rem;
      background-color: var(--auro-color-background-lightest);
      padding: var(--auro-size-xxl) var(--padding);
      border-radius: 0.25rem;
      display: flex;
      flex-direction: column;
      box-shadow: 0 0.25rem 0.75rem rgb(0 0 0 / 10%);
    }
  }
</style>
