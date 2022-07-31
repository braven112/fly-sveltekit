<auro-header level="3" margin="top" size="none" display="500">Auto Column Layout</auro-header>
<p>This uses no media queries. We simply set a minimum column size and auto-fill the rest.  This is ideal for use cases where the content is dynamic and setting up a specific layout isn't possible or necessary.</p>
<div class="auto-grid">
  <div class="grid-item">
    <div class="avatar-details">
      <auro-avatar md code="ANC" />
      <div class="avatar-cityname">Anchorage, AK</div>
      <div class="avatar-airport fineprint">ANC-Anchorage Intl.</div>
    </div>
  </div>
  <div class="grid-item">
    <div class="avatar-details">
      <auro-avatar md code="KOA" />
      <div class="avatar-cityname">Kailua, HI</div>
      <div class="avatar-airport fineprint">KOA-Keahole</div>
    </div>
  </div>
  <div class="grid-item">
    <div class="avatar-details">
      <auro-avatar md code="MCO" />
      <div class="avatar-cityname">Orlando, FL</div>
      <div class="avatar-airport fineprint">MCO-Orlando Intl.</div>
    </div>
  </div>
  <div class="grid-item">
    <div class="avatar-details">
      <auro-avatar md code="ZIH" />
      <div class="avatar-cityname">Zihuatanejo, Mexico</div>
      <div class="avatar-airport fineprint">Ixtapa/Zihuatanejo Intl.</div>
      <div class="avatar-airport fineprint">ZIH</div>
    </div>
  </div>
  
  <div class="grid-item">
    <div class="avatar-details">
      <auro-avatar md code="HNL" />
      <div class="avatar-cityname">Honolulu, HI</div>
      <div class="avatar-airport fineprint">Honolulu Intl./Oahu</div>
      <div class="avatar-airport fineprint">HNL</div>
    </div>
  </div>
  <div class="grid-item">
    <div class="avatar-details">
      <auro-avatar md code="LIH" />
      <div class="avatar-cityname">Lihue, HI</div>
      <div class="avatar-airport fineprint">Lihue/Kauai</div>
      <div class="avatar-airport fineprint">LIH</div>
    </div>
  </div>
  <div class="grid-item">
    <div class="avatar-details">
      <auro-avatar md code="SAT" />
      <div class="avatar-cityname">San Antonio, TX</div>
      <div class="avatar-airport fineprint">San Antonio Intl.</div>
      <div class="avatar-airport fineprint">SAT</div>
    </div>
  </div>
  <div class="grid-item">
    <div class="avatar-details">
      <auro-avatar md code="SJD" />
      <div class="avatar-cityname">San Jose del Cabo, Mexico</div>
      <div class="avatar-airport fineprint">Los Cabos Intl.</div>
      <div class="avatar-airport fineprint">SJD</div>
    </div>
  </div>
  <div class="grid-item">
    <div class="avatar-details">
      <auro-avatar md code="SJC" />
      <div class="avatar-cityname">San Jose, CA</div>
      <div class="avatar-airport fineprint">San Jose Intl.</div>
      <div class="avatar-airport fineprint">SJC</div>
    </div>
  </div>
  <div class="grid-item">
    <div class="avatar-details">
      <auro-avatar md code="SJO" />
      <div class="avatar-cityname">San Jose, Costa Rica</div>
      <div class="avatar-airport fineprint">San Jose Juan Santamaria</div>
      <div class="avatar-airport fineprint">SJO</div>
    </div>
  </div>
  <div class="grid-item">
    <div class="avatar-details">
      <auro-avatar md code="SBP" />
      <div class="avatar-cityname">San Luis Obispo, CA</div>
      <div class="avatar-airport fineprint">San Luis Obispo</div>
      <div class="avatar-airport fineprint">SBP</div>
    </div>
  </div>

  <div class="grid-item">
    <div class="avatar-details">
      <auro-avatar md code="SEA" />
      <div class="avatar-cityname">Seattle, WA</div>
      <div class="avatar-airport fineprint">Seattle/Tacoma Intl.</div>
      <div class="avatar-airport fineprint">SEA</div>
    </div>
  </div>
</div>

<style>
  .auto-grid {
    --auto-grid-min-size: 16rem;
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(var(--auto-grid-min-size), 1fr));
    gap: var(--auro-size-xs);
  }

@media screen and (min-width: 660px) {
	.auto-grid {
		gap: var(--auro-size-sm);
	}
}

@media screen and (min-width: 1024px) {
	.auto-grid {
		gap: var(--auro-size-md);
	}
}

@media screen and (min-width: 1232px) {
	.auto-grid {
		gap: var(--auro-size-lg);
	}
}

@media screen and (min-width: 1233px) {
	.auto-grid {
		gap: var(--auro-size-xl);
	}
}
  @import "../../globalGridExamples.css";
</style>
