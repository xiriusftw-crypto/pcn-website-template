---
enable: true
imagePosition: "left"

images:
  large: "/images/skill/skill-1.png"
  small: "/images/skill/skill-2.jpg"

title: |
  We provide perfect IT & Financial solutions
subtitle: |
  With a team deadset on providing the best of services, we make sure to set clear priorities and goals to provide to unique needs.
description: |
  We plan, project and provide, always ready to optimize and harbor future choices and potential.
# EXTRATYPE OPTIONS: "skills" | "list-x" | "list-y" | "stats" | "none"
extraType: "list-x"

# SHARED BUTTON CONFIGURATION (Applies to all section buttons)
buttons:
  - enable: false # Boolean: true | false
    label: "Explore Our Services"
    url: "/services/"
    tag: "a" # Enum: a | button
    variant: "fill" # Enum: fill | fill-white | outline | text | circle
    hoverEffect: "magnetic-text-flip" # Enum: text-flip | creative-fill | magnetic | magnetic-text-flip
    icon: # Object
      enable: true
      name: "ArrowUpRight" # String: Lucide Icon Name - https://lucide.de v/icons/?search=
      position: "right" # Enum: left | right (Note: text variant is always right)
    rel: "noopener"
    target: "_blank" # String: _blank | _self
    class: "" # String: Additional button Tailwind classes

listItems:
  - title: "Provide Skills<br />Services"
    icon: "Settings"
  - title: "Urgent Support<br />For Clients"
    icon: "Headphones"
---
