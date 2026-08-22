# jeremybernsdorff.com Portfolio V5

## Site structure

- `index.html` — portfolio home
- `experience.html` — professional experience
- `vmware.html` — VMware / Windows Server / AD DS lab
- `microsoft365.html` — Microsoft 365 / Entra / Intune administration
- `software.html` — BroadbandOps + Lotto Lab
- `assets/css/site.css`
- `assets/js/site.js`
- `assets/images/` — place renamed images here

## Image naming map

### Experience
- `exp_trueblue_logo.png`
- `exp_disys_logo.png`
- `exp_boeing_logo.png`
- `exp_dellemc_logo.png`
- `exp_teksystems_logo.png`
- `exp_amfam_logo.png`
- `exp_autoliv_logo.png`
- `exp_pg_logo.png`

### VMware / Windows lab
- `vmware_overview_fleet.png`
- `vmware_servermanager_adds.png`
- `vmware_aduc_computers.png`
- `vmware_aduc_users_groups.png`
- `vmware_gpo_management.png`
- `vmware_powershell_admin.png`

### Microsoft 365 administration
- `m365_admin_center_home.png`
- `m365_entra_users_groups.png`
- `m365_hybrid_identity_sync.png`
- `m365_intune_fleet.png`
- `m365_intune_configuration_policy.png`
- `m365_intune_compliance_policy.png`

### BroadbandOps
- `software_broadbandops_hero.png`
- `software_broadbandops_02.png`
- `software_broadbandops_03.png`
- `software_broadbandops_04.png`

### Lotto Lab
- `software_lottolab_gamechooser.png`
- `software_lottolab_02.png`
- `software_lottolab_03.png`
- `software_lottolab_04.png`

## Important
The scaffold currently displays clear IMAGE placeholders rather than broken `<img>` elements.
After you decide the final screenshots and rename them, replace the placeholder blocks with:
`<img src="assets/images/FILENAME.png" alt="...">`

This keeps the content decisions under your control while preserving the page structure.


## V5 corrections
- Production-facing copy pass applied.
- Experience and software carousels now have visible controls/dots and swipe/keyboard support.
- Current vs previously held certifications separated.
- VMware count updated to two Windows Server 2025 instances.
- Image filename map remains in README and visible placeholders remain until actual images are wired.


## V6 — Employment logo sprite support

Added:

- `assets/css/employment-logos.css`
- Experience-page sprite classes for TrueBlue, DISYS, Boeing, Dell EMC, TEKsystems, American Family, Autoliv, and P&G
- `SPRITE_SETUP.md`

Expected sprite filename:

`assets/images/employment_logos_sprite.png`

The default CSS map assumes a 4-column × 2-row sprite. See `SPRITE_SETUP.md` before publishing the logo asset.


## V7 — Downloadable learning documentation

Added one home-page section:

**Documentation in Practice**

The bundled PDF is located at:

`assets/docs/M365BP_Virtualized_Infrastructure_Build_and_Domain_Deployment.pdf`

The home page links to it with the HTML `download` attribute.

The PDF supports the portfolio statement that lab work is documented with:
- architecture and control-plane notes
- troubleshooting and resolution
- PowerShell / administrative commands
- validation steps
- evidence gaps
- operational lessons learned
