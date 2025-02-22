---
created by xreped
---
# Entity Class

## Properties

### **canBeCollidedWith()**
`canBeCollidedWith()`

Returns true if other Entities should be prevented from moving through this Entity.
### **canBePushed**
`canBePushed()`

Returns true if this entity should push and be pushed by other entities when colliding.
### **canRenderOnFire**
`canRenderOnFire()`

Return whether this entity should be rendered as on fire.
### **doBlockCollisions**
`doBlockCollisions()`

Checks for block collisions, and calls the associated onBlockCollided method for the collided block.
### **doesEntityNotTriggerPressurePlate**
`doesEntityNotTriggerPressurePlate()`

Return whether this entity should NOT trigger a pressure plate or a tripwire.

## Methods

### **addEntityID**
`addEntityID(NBTTagCompound*)`

Adds the ID of this entity to the NBT given
### **addNotRiddenEntityID**
`addNotRiddenEntityID(NBTTagCompound*)`

Description not provided
### **addVelocity**
`addVelocity(Vector3)`

Adds to the current velocity of the entity. Args: x, y, z
### **applyEntityCollision**
`applyEntityCollision(Entity*)`

Applies a velocity to each of the entities pushing them away from each other. Args: entity

### **copyDataFrom**
`copyDataFrom(Entity*, boolean)`

Description not provided
### **copyLocationAndAnglesFrom**
`copyLocationAndAnglesFrom(Entity*)`

Description not provided
### **dropItem**
`dropItem(int, int)`

Drops an item stack at the entity's position. Args: itemID, count

## Events 

### **attackEntityFrom**
`attackEntityFrom(DamageSource*, number)`

Called when the entity is attacked.

