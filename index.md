# The Coffee House Studio

# Unity Asset Store
### Drag N Drop 3D
#### Introduction
Drag N Drop 3D aims to provide unity developer with a simple and easy way to create a drag and drop functionality from UI-space to a predefined world-space destination in 3D environment. Feature:
- Configurable Distance:The distance between dragging object and destination  in world space which is considered as close enough to drop the item.
- Auto Move Back: Move the dragging object back when the distance to target larger than the configured distance
- Identical Rotation: Dragging object is in 3D and have identical rotation as the destination object while the destination object is rotate.
- Work When Rotate: Work even when the destination object is rotating.
- Easy to Configure: Distance and target, source list is configurable through the editor
#### User Guide
Create a DragNDropConfig game object and then add DragNDropConfig component to the the game object.
![DragNDropConfig](https://user-images.githubusercontent.com/5996087/88127628-57007180-cbfe-11ea-8ac9-bbf6d0cfac98.png)
Configure DragNDropConfig component
![DragNDropConfig Component](https://user-images.githubusercontent.com/5996087/88127707-87e0a680-cbfe-11ea-9acb-56cb23cbc4ef.png)
Camera: Specify camera which the destination game object is viewed by. If empty, the main camera is used
Good distance: The distance between dragging object and destination  in world space which is considered as close enough to drop the item.
DragNDrops:  A List contains drag and drop detail.
Source: Transform in UI which the drag item will start from.
Destination: Transform in World space which the drag item will end at.
Moving prefab: Prefab of the item which is shown while item is being dragged.
#### Credit
Road roller model made by [Poly grunt](https://assetstore.unity.com/publishers/47845) . Get it from [here](https://assetstore.unity.com/packages/3d/vehicles/land/polygrunt-construction-vehicles-168884#content)

Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
