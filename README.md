# Vim Key Bindings Cheat Sheet

## Navigation and Window Management

- **Next and Previous Editor Tab**
  - `<Space>tn`: Next editor tab.
  - `<Space>tN`: Previous editor tab.

- **Focus Editor Groups**
  - `<Space>fn`: Focus next editor group.
  - `<Space>fN`: Focus previous editor group.

- **Move Editor Between Groups**
  - `<Space>vif`: Move editor to first group.
  - `<Space>vil`: Move editor to last group.
  - `<Space>vin`: Move editor to next group.
  - `<Space>viN`: Move editor to previous group.

## File and Editor Management

- **Closing Editors**
  - `<Space>ceg`: Close editors in group.
  - `<Space>coe`: Close other editors.
  - `<Space>ceo`: Close editors in other groups.

- **File Operations**
  - `<Space>w`: Save file (`:w!`).
  - `<Space>q`: Close editor (`:q!`).
  - `<Space>x`: Save and close editor (`:x!`).

## Editor Splitting

- **Split Editor**
  - `<Space>sh`: Split editor left.
  - `<Space>sj`: Split editor down.
  - `<Space>sk`: Split editor up.
  - `<Space>sl`: Split editor right.

## Code Navigation and Operations

- **Problems and Markers**
  - `<Space>pn`: Go to next problem/marker.
  - `<Space>pN`: Go to previous problem/marker.

- **Rename and Quick Actions**
  - `<Space>r`: Rename symbol.
  - `<Space>a`: Quick fix actions.

- **Toggle Views and Panels**
  - `<Space>l`: Toggle sidebar visibility.
  - `<Space>h`: Toggle auxiliary bar.
  - `<Space>o`: Quick open.
  - `<Space>i`: Open Quick Chat with Copilot.

## Git and Source Control

- **Git Operations**
  - `<Space>gf`: Focus on SCM.
  - `<Space>gd`: Clean changes in Git.
  - `<Space>gs`: Stage changes in Git.
  - `<Space>gsN`: Go to previous dirty diff.

- **Navigation in Changes**
  - `<Space>cn`: Next change.
  - `<Space>cN`: Previous change.

## Formatting and Quick Fixes

- **Formatting and Fixes**
  - `<Space>fd`: Format document.
  - `<Space>ds`: Compare with saved version.
  - `<Space>dp`: Diff with previous version in GitLens.

## Miscellaneous

- **Other Commands**
  - `leader 1`, `leader 2`, `leader 3`: Focus on the first, second, and third editor group, respectively.
