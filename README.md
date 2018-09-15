# admin_blocks
Minetest Mod - Protect server from grief and node spams by requiring privs to place certain blocks

To block a new node, add the following code to init.lua at line 10 and change <modname> to modname:

-- Restricted items
local restricted_items = {
    'bucket:bucket_lava',
    'technic:lava_can',
    'technic:corium_source',
    'gloopblocks:rainbow_block_horizontal',
    'gloopblocks:rainbow_block_diagonal',
    'yaycat:yaycat',
    'yaycatrainbow:yaycatrainbow',
    'default:lava_source',
    'default:water_source',
    'default:river_water_source',
    'fire:basic_flame',
    'fire:perminant_flame',
    '<modname>',
}

