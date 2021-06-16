## [v0.3.0] - 2021-06-16 

- [2021-06-08]

    Added ability to immediately run a scheduled object that is submitted to spark.queueUpdate.  Example: ```ts  // Setting `NOW` argument to insert the update object into the current // active schedule loop spark.queueUpdate( {onScheudedUpdate:()=>console.log("updated now")}, 0,0, true /*<= forces the update to occur in current loop */ )  ```

## [v0.2.0] 

- No changes recorded prior to this version.