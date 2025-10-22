```mermaid
flowchart TD
	A["Is the current day doing more tasks than the average task/day?"] -- Yes --> B["Get beer"]
	A -- No --> C("Next day")
	C ---> A
```
