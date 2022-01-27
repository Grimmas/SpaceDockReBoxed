# Change-log

* 0.1.0
  * Mod Support
    * ExLaunchPad
    * ConnectedLivingSpace
    * ShipYard
  * New
    * In-build reaction wheel
    * 9 more stack nodes
    * explosionPotential = 10
    * Editor
      * bulkheadProfiles = size2
      * Adjusted
      * name
      * author
      * maximum_drag = 2 -> 3
      * minimum_drag = 3 -> 2
      * Editor
         * category = Structural -> Utility
         * TechRequired
         * cost
         * title
         * entryCost
         * manufacturer
         * description
  * Fixed
    * maximum_drag < minimum_drag
* 0.2.0
   * Removed electric charge resource and the reaction wheel
   * 2 additional sets (6 more) of SpaceDocks in different Bulkhead sizes.
   * Rebalanced parts
   * Adjusted
      * name
      * node_stack_*
      * mass (based on some ridiculous math)
      * Editor
         * title
         * manufacturer
         * description
      * New
         * Editor
              * tags = launchpad shipyard dock
              * Agency "SpaceShip²Yard Enterprises"
      * Support
         * ExTarget
         * ShipYard
   * Fixed
      * Invalid stack node id naming
* 0.2.1
   * Fixed Wrong description text for a technode
   * Mod Support KIS (KISPickup)
   * Reduced entry costs

0.3.0
	Adoption by Linuxgurugamer
	Reformatted all files
	Fixed bad characters
	Merged @Denko666's changes with the original

0.3.0.1
	Thanks to @Tonka Crash for this:
		Added ":NEEDS[ConnectedLIvingSpace]" to the CLS module def in each of the parts

0.3.0.2
	Renamed repo back to SpaceDockReBoxed
    
0.3.0.3
    Fixed URL in .version file

0.3.0.4
	Thanks to github user @TonkaCrash
		Fix CLS Needs statements
