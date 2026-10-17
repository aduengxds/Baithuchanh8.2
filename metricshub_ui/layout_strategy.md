# Layout Strategy - MetricsHub

## 1. Navbar - Flexbox

Navbar sử dụng CSS Flexbox.

Các thành phần chính gồm:

- Logo
- Navigation links
- Login / Signup actions

Sử dụng:

- `display: flex`
- `justify-content: space-between`
- `gap`
- `flex-wrap`

Không sử dụng các cột có chiều rộng cố định.

Khi màn hình nhỏ, navigation có thể xuống dòng thông qua `flex-wrap`.

---

## 2. Dashboard - CSS Grid

Dashboard sử dụng CSS Grid.

```css
.dashboard-grid {
    display: grid;
    grid-template-columns: repeat(4, minmax(0, 1fr));
}