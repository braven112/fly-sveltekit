<script>
  import { page } from "$app/stores";
</script>

<header>
  <div class="container">
    <div class="flex flex-row">
      <auro-lockup>
        <span slot="title">Auro</span>
        <span slot="subtitle">Examples & Demos</span>
      </auro-lockup>
      <nav>
        <auro-dropdown id="common" aria-label="Label content for screen reader">
          <div class="infobar">
            <div>
              <div class="infobaritem"><auro-header level="4" margin="both" size="none" display="300">Booking</auro-header></div>
              <div class="infobaritem">
                <auro-hyperlink href="#">
                  <auro-icon accent category="terminal" name="boarding-pass-stroke" />
                </auro-hyperlink>
                <auro-hyperlink href="#"><span>ID90</span></auro-hyperlink>
              </div>
              <div class="infobaritem">
                <auro-hyperlink href="#">
                  <auro-icon accent category="in-flight" name="elite" />
                </auro-hyperlink>
                <auro-hyperlink href="#"><span>MyIDTravel</span></auro-hyperlink>
              </div>
              <div class="infobaritem">
                <auro-hyperlink href="#">
                  <auro-icon accent category="interface" name="contract-fare" />
                </auro-hyperlink>
                <auro-hyperlink href="#"><span>Confirmed Employee Tickets</span></auro-hyperlink>
              </div>

              <div class="infobaritem">
                <auro-hyperlink href="#">
                  <auro-icon accent category="destination" name="hotel" />
                </auro-hyperlink>
                <auro-hyperlink href="#"><span>ID90 Hotels</span></auro-hyperlink>
              </div>
            </div>
          </div>
          <div class="infobar">
            <div>
              <div class="infobaritem">
                <auro-header level="4" margin="both" size="none" display="300">Manage Travel </auro-header>
              </div>
              <div class="infobaritem">
                <auro-hyperlink href="#" type="nav">
                  <auro-icon accent category="interface" name="account-stroke" />
                </auro-hyperlink>
                <auro-hyperlink href="#" type="nav"><span>Annita Holiday</span></auro-hyperlink>
              </div>
              <div class="infobaritem">
                <auro-hyperlink href="#">
                  <auro-icon accent category="in-flight" name="boarding" />
                </auro-hyperlink>
                <auro-hyperlink href="#"><span>Guest Passes</span></auro-hyperlink> <auro-badge pill advisory>12</auro-badge>
              </div>
              <div class="infobaritem">
                <auro-hyperlink href="#">
                  <auro-icon accent category="interface" name="premium-class-upgrade-available" />
                </auro-hyperlink>
                <auro-hyperlink href="#"><span>PST Credits</span></auro-hyperlink>
                <auro-badge pill>5</auro-badge>
              </div>
              <div class="infobaritem">
                <auro-hyperlink href="#">
                  <auro-icon accent category="interface" name="mixed-cabin-itinerary" />
                </auro-hyperlink>
                <auro-hyperlink href="#"><span>Exchange Credits For Passes</span></auro-hyperlink>
              </div>
              <div class="infobaritem">
                <auro-hyperlink href="#" type="nav">
                  <auro-icon accent category="terminal" name="booking-stroke" />
                </auro-hyperlink>
                <auro-hyperlink href="#" type="nav"><span>Guest Pass History</span></auro-hyperlink>
              </div>
            </div>
          </div>
          <div class="infobar">
            <div>
              <div class="infobaritem"><auro-header level="4" margin="both" size="none" display="300">Travel Info</auro-header></div>
              <div class="infobaritem">
                <auro-hyperlink href="#" type="nav">
                  <auro-icon accent category="in-flight" name="luggage" />
                </auro-hyperlink>
                <auro-hyperlink href="#" type="nav"><span>Travel Guidelines</span></auro-hyperlink>
              </div>
              <div class="infobaritem">
                <auro-hyperlink href="#" type="nav">
                  <auro-icon accent category="interface" name="global-language" />
                </auro-hyperlink>
                <auro-hyperlink href="#" type="nav"><span>Pass Agreements</span></auro-hyperlink>
              </div>
            </div>
          </div>
          <auro-icon category="interface" name="navigation-menu" slot="trigger" tabindex="0" />
        </auro-dropdown>
      </nav>
    </div>
  </div>
</header>

<style>
  .infobar {
    flex: 1;
    align-self: center;
    display: flex;
    justify-content: space-between;
    padding: var(--padding);
  }
  .infobar + .infobar {
    padding-top: 0;
  }
  .infobar > div {
    display: flex;
    flex-direction: column;
  }
  .infobaritem {
    padding: 0 var(--auro-size-md) 0 0;
  }

  header {
    box-shadow: 0 0.25rem 0.75rem rgb(0 0 0 / 10%);
  }
  @media screen and (min-width: 1024px) {
    nav {
      align-self: center;
      flex-grow: 10;
      justify-content: flex-end;
      display: flex;
    }
  }
  auro-dropdown#common {
    padding-left: var(--padding);
  }
  auro-hyperlink span {
    line-height: 1.75rem;
    margin-left: 0.5rem;
  }
  auro-lockup {
    flex-basis: 25rem;
    flex-grow: 1;
    flex-shrink: 1;
  }
  .container {
    display: block;
    max-width: 1232px;
    margin: auto;
    padding: var(--padding);
  }

  .flex {
    display: flex;
    flex-direction: column;
  }

  .flex-row {
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
  }
</style>
