# Maps Organization

This directory contains all world files organized by minigame type.

## Current Maps

### Lobby
- `main-lobby/` - Primary server hub with portals to minigames

### BedWars
- `bw-aquarius/` - 4v4v4v4 water-themed map
- `bw-fortress/` - 4v4v4v4 medieval castle map
- `bw-lighthouse/` - 2v2v2v2 coastal map

### SkyWars
- `sw-tropical/` - Solo tropical islands
- `sw-nether/` - Solo nether-themed map
- `sw-canyon/` - Team map with canyon theme

### TNTRun
- `tr-classic/` - Traditional rectangular arena
- `tr-spiral/` - Spiral-shaped challenging arena

### Rush Game (Custom)
- `rg-speedway/` - Racing track with obstacles
- `rg-parkour/` - Parkour-style racing course

## Map Specifications

### BedWars Requirements
- Team islands with beds and resource generators
- Diamond and emerald generators in center/sides
- Void boundaries at Y=0
- Spawn protection regions

### SkyWars Requirements
- Balanced island sizes and distances
- Chest locations for loot
- Center island for mid-game fights
- Void boundaries

### Custom Game Requirements
- Spawn points for all players
- Checkpoint markers
- Clear boundaries and rules
- Performance optimized (minimal entities)

## Adding New Maps

1. Create in development server
2. Test thoroughly with target player count
3. Set up spawn points and regions
4. Create documentation file
5. Export schematic backup
6. Add to plugin configuration