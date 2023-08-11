# _Reconsiler_

Reconsiler is basic attemp to replicate react at the very basic level, It deepens the understanding of how DOM manipulation uner the hood works and how react manages to update the states



```sh
/**
 * -----------------------------------------------------
 * Below code shows the usage of class and its functions
 * below is the sampl case where state got updated after 3 sec
 */

let reconsile = new MakeState(state)

reconsile.init(howUserwantToAppendMyStateToHtml)

setTimeout(()=>{
    reconsile.updateState(updatedState)
}, 3000)
```


