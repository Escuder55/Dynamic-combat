February 2018 UPDATE
-------------------------------------
*ANS_ToggleWeaponAttachment-Player was changed to AN_ToggleHandItems
*CollisionHandlerComponent is no longer limited to skeletal meshes, static mesh can be used now as well  
*New function in MontagesManagerComponent, 'GetRandomMontageIndex'
*New function in BPL_CombatSystemFunctionLibrary 'GetStatisticComponent' which allows to get *StatisticComponent by it's type (Health/Stamina)
*AI Strafing behavior works now on curved locations
*All used input keys are now stored in ConfigFile (Edit->ProjectSettings->Input)
*RotateTowardsTarget logic was moved entirely from BP_BaseAI to Anim notify (ANS_RotateTowardsTarget)
*Equipment Component Added (Allows player to equipp weapons/armor parts)
*Inventory Component Added (Allows player to store, use and drop items)
*Behavior Component Added (for now it only allows to specify enemies of AI, will be extended in next updates)
*New event dispatcher OnTargetChanged added to DynamicTargetingComponent
*New event dispatcher OnValueChanged added to StatisticComponent

Changes are described more precisely in attached pdf file