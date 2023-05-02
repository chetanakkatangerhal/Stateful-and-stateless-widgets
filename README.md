# Stateful-and-stateless-widgets

When the app first launches, the star is solid red, indicating that this lake has previously been favorited. The number next to the star indicates that 41 people have favorited this lake. After tapping the star removes its favorited status, replacing the solid star with an outline and decreasing the count. Tapping again favorites the lake, drawing a solid star and increasing the count.

To accomplish this create a single custom widget that includes both the star and the count, which are themselves widgets. Tapping the star changes state for both widgets, so the same widget should manage both.
