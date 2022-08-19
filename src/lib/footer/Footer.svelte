<footer>
  <div class="footer-container">
    <div class="grid">
      <div class="col-xs-10">
        <div class="contact-info">
          <auro-header level="3" margin="top" size="none" display="500">Have questions? Contact us.</auro-header>
          <p>Or, call us at 1-844-899-3617 (Employees Only) Monday - Friday, 8am - 4:30pm PST <br /></p>
          &copy; 2021 Alaska Airlines, Inc. All rights reserved.
        </div>
      </div>
      <div class="col-xs-2 footer-links">
        <auro-header level="3" margin="top" size="none" display="500">More info</auro-header>
        <auro-hyperlink target="_blank" ondark href="https://mango-hill-04caf201e.1.azurestaticapps.net">Trip History Route Map</auro-hyperlink>
        <auro-hyperlink target="_blank" ondark href="https://www.alaskaair.com/content/airports">Our Airports</auro-hyperlink>
        <auro-hyperlink target="_blank" ondark href="https://www.alaskaair.com/content/travel-info/our-aircraft">Our Aircraft</auro-hyperlink>
      </div>
    </div>
  </div>
</footer>

<style>
  @import "../../globalGrid.css";
  footer {
    background-color: var(--auro-color-background-darker);
    color: var(--auro-color-text-primary-on-dark);
    font-size: var(--auro-text-body-size-xs);
  }
  .footer-container {
    display: block;
    max-width: 1232px;
    margin: auto;
    padding: var(--auro-size-xxxl) var(--padding);
  }
  .footer-links {
    display: flex;
    flex-direction: column;
    text-align: right;
  }
</style>
