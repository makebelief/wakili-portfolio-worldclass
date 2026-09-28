# Wakili wa Tech Portfolio — Light Brand Edition

Rebuilt to match the production Wakili wa Tech design language:
- Manrope typography
- warm white / cream surfaces
- black primary UI
- purple #6928fb
- yellow highlight #ffd84d
- blue/cyan/green spectrum accents
- screenshot-based project previews instead of iframes

Project cards use WordPress mShots to render public website thumbnails. If a thumbnail service fails, the card falls back to a branded project placeholder and the live-site link still works.


## V3 preview fix
- Removed the WordPress mShots thumbnail service entirely.
- Project cards now use Open Graph/social-card, hero, or project-hosted imagery from the actual live websites.
- Projects without a usable image render a branded Wakili wa Tech fallback card instead of a broken/black preview.
- Favicon now uses the official Wakili wa Tech production favicon.
