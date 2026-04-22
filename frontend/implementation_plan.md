# Build Guardian Frontend

Me build Guardian frontend. Make UI for cameras and alerts. Use React and Tailwind CSS.

## User Review Required

> [!IMPORTANT]
> Need you say YES. Me will make new app in `frontend/app`. Me use Vite for fast build. Me use Tailwind CSS for style. Me use `lucide-react` for icons. All TypeScript.

## Proposed Changes

### Setup Environment
- Use `npm` make Vite React-TS app in `frontend/app`.
- Install Tailwind CSS. Add config.
- Install `lucide-react` for picture icons.

### Design Atoms & Molecules
- `Sidebar`: Menu on left side.
- `StatCard`: Boxes on top (Active Cameras, Alerts).
- `CameraFeedCard`: Box showing one camera with status.
- `AlertBanner`: Big red bar on top for warnings.
- `ThreatPanel`: Detail box showing threat level and info.

### App Pages
- `Dashboard`: Main view pattern. Show many cameras. Show stats.
- `CameraView`: Focus view pattern. Show one large camera. Show threat details.

## Open Questions

> [!WARNING]
> Me use simple state to switch between Dashboard and CameraView? Or me install `react-router-dom`? Simple state better for caveman. You agree?

## Verification Plan

### Code Check
- Run `npm run build`. App compile with no TS errors.
- TS interfaces defined. No `any` used.

### Look Check
- You run `npm run dev`. You see beautiful Guardian app. It look like your pictures.
