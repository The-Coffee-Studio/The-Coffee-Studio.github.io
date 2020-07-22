# The Coffee Studio
The coffee studio is a small studio created by a coffee addicter who love to make small things joyful. We are focusing on Unity-based casual games for the past serveral years.


# Drag N Drop 3D

## Introduction
![Drag N Drop 3 D Unity](https://youtu.be/J6dgJVQ4P3Q)
Drag N Drop 3D is an unity asset aims to provide unity developer with a simple and easy way to create a drag and drop functionality from UI-space to a predefined world-space destination in 3D environment. Feature:
* **Configurable Distance:** The distance between dragging object and destination  in world space which is considered as close enough to drop the item.
* **Auto Move Back:** Move the dragging object back when the distance to target larger than the configured distance
* **Identical Rotation:** Dragging object is in 3D and have identical rotation as the destination object while the destination object is rotate.
* **Work When Rotate:** Work even when the destination object is rotating.
* **Easy to Configure:** Distance and target, source list is configurable through the editor.

## User Guide
Create a DragNDropConfig game object and then add DragNDropConfig component to the the game object.

![DragNDropConfig](https://user-images.githubusercontent.com/5996087/88127628-57007180-cbfe-11ea-8ac9-bbf6d0cfac98.png)

Configure DragNDropConfig component

![DragNDropConfig Component](https://user-images.githubusercontent.com/5996087/88127707-87e0a680-cbfe-11ea-9acb-56cb23cbc4ef.png)


* **Camera:** Specify camera which the destination game object is viewed by. If empty, the main camera is used
* **Good distance:** The distance between dragging object and destination  in world space which is considered as close enough to drop the item.
* **DragNDrops:**  A List contains drag and drop detail.
* **Source:** Transform in UI which the drag item will start from.
* **Destination:** Transform in World space which the drag item will end at.
* **Moving prefab:** Prefab of the item which is shown while item is being dragged.

## Credit
Road roller model made by [Poly grunt](https://assetstore.unity.com/publishers/47845) . Get it from [here](https://assetstore.unity.com/packages/3d/vehicles/land/polygrunt-construction-vehicles-168884#content)

# Contact
Email: the.coffee.std@gmail.com
