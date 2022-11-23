<style>
            .breadcrumb {
              color: var(--auro-color-text-secondary-on-light);
              line-height: 2;
            }

            .breadcrumb-divider {
              color: var(--auro-color-icon-primary-on-light);
              height: var(--auro-size-300, 24px);
              margin-left: 4px;
              margin-right: 4px;
            }

            .breadcrumb-home {
              margin-right: 6px;
            }
          </style>
          <div class="breadcrumb">
            <auro-hyperlink nav href="/next" type="nav">
              <auro-icon class="breadcrumb-home" category="interface" name="home-stroke" customColor></auro-icon>Home
            </auro-hyperlink>
            <auro-icon class="breadcrumb-divider" category="interface" name="chevron-right" customColor></auro-icon>
            <auro-hyperlink nav href="/next">
              Level 1
            </auro-hyperlink>
            <auro-icon class="breadcrumb-divider" category="interface" name="chevron-right" customColor></auro-icon>
            <auro-hyperlink nav href="/next">
              Level 2
            </auro-hyperlink>
            <auro-icon class="breadcrumb-divider" category="interface" name="chevron-right" customColor></auro-icon>
            <auro-hyperlink nav href="/next">
              Level 3
            </auro-hyperlink>
            <auro-icon class="breadcrumb-divider" category="interface" name="chevron-right" customColor></auro-icon>
            Current
        </div>