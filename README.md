# OakwoodWishlist

# Events

#### OnEnterVehicle and OnLeaveVehicle
> Self explainatory

# Functions

#### setInstance and getInstance
> Would allow creating multiple virtual worlds. Players and entities in instance #1 would not see players and entities in instance
> Example: entity.setInstance(instanceIndex), entity.getInstance()

#### attachToEntity
> Attaching players and objects to eachother
> Example: entity.attachToEntity(entityToAttachTo)

#### setVar getVar
> Save data in entities
> Example: entity.setVar({var1: value1, var2: value2})

#### setColshape
> Create colision shape and trigger events when entering/exiting it with onEnterColshape and onExitColshape
> Example: var colshapeName = setColshape.circle(x, y, radius)
> onEnterColshape(colshapeName, entity) => *Do something*
