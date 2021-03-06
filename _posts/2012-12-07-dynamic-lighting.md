---
layout: default
published: true
categories: tabletop_toolbox
title: Dynamic Lighting
---

<div class='alert alert-info'>This feature is only available to paid subscribers-- both Mentor and Supporter levels.  If this is something you’re interested in, please visit the <a href="https://app.roll20.net/account/supporter/">Supporter Page</a>.</div>

#What is Dynamic Lighting?

<img style="display: block; margin-left: auto; margin-right: auto" src="/images/Dynamic_Lighting.jpg" alt="Dynamic Lighting" />
<p style="text-align:center">*Dungeon Art by [Greg Taylor]( https://marketplace.roll20.net/browse/set/50/diy-dungeon-blank-pack),  Token Art by [Devin Night]( https://marketplace.roll20.net/browse/set/2/devin-token-pack-1-characters)*</p>

Dynamic Lighting is an advanced map lighting tool currently available to Mentor & Subscriber users. It calculates line of sight on the fly as tokens are moved across the tabletop.

#The Dynamic Lighting Layer

<img style="float:left; margin-right: 10px;" src="/images/DL_Layer.jpg" alt=”The Dynamic Lighting Layer” />

In addition to the Map & Background Layer, the Object & Token Layer and the GM Overlay Layer is the Dynamic Lighting Layer. This fourth layer’s purpose is for laying down lines and shapes that will serve as walls and/or obstacles that will block out light or line of sight.

<div style="clear: both; height: 10px;"></div>

#How to Activate Dynamic Lighting

Open up your [Page Settings](/page-toolbar-page-settings) and check the checkbox to activate Dynamic Lighting for that page. *You can use Fog of War In combination with Dynamic Lighting, but one is not dependant on the other to function.*

If you or your players suffer from sluggish dynamic lighting render results you might want to consider checking the option **Only Update on Drop**. What this option does when checked is that the tabletop only redraws the dynamic lighting *after* a token has been picked up and placed elsewhere on the map. This can lessen the render burden for users running on slower connection speeds or when a GM is working with a very large or complex map.

#How to Add Light Obstructions

<img style="float:left; margin-right: 10px;" src="/images/DL_Walls.jpg" alt="Dynamic Lighting Wall Design" />
While on the Dynamic Lighting Layer, you can use all of the drawing tools available to create lines and shapes to draw walls, columns, doors, etc. You can also utilize color to help differentiate different types of light obstructions (ex. lime green for stationary dungeon walls and bright red for doors). 

Use the drawing tools to draw outlines of all the walls and other pieces of the map that you want to block light. We suggest using the Polygon Tool for best results.

<!--There are two very important factors one should consider in the design of their Dynamic Lighting scheme:
<ol>
<li>Use fully closed shapes/polygons whenever possible.</li>
<li>Avoid designs where a Token could intentionally wander *inside* a shape – don’t use convex lines.</li>
</ol>

While this approach might look very inefficient in comparison to simply tracing the perimeter of a dungeon map’s walls, this does ensure that lighting will work in a predictable fashion. Dynamic Lighting gets very unreliable and unpredictable when you use open, convex lines. -->

<div style="clear: both; height: 10px;"></div>

#Adding Light

Now that you have your obstacles drawn out on the Dynamic Lighting Layer, you now have to add light to your Page. Light is emitted via tokens. You can manage this in **Token Settings**. Under the settings for Auras is the option **Emits Light**. This option allows you to enter a light radius amount and gives you a checkbox for **All Players See Light**. When the checkbox is left unchecked, the only player(s) who can see that token’s light emission are those who have assigned permission to that token.