# Controlling the agent

### @explicitHints 1

### @activities true

## First Activity

### Agent destroy

Open the ``||agent:AGENT||`` category and drag an ``||agent:agent destroy||`` block into the ``||player:on chat command||`` block named **destroy**.

Try to have the agent destroy a block in its path. Send the command **destroy** in the Minecraft chat to run the code in the **destroy** ``||player:on chat command||``.


#### ~ tutorialhint


```blocks
player.onChat("destroy", function () {
    agent.destroy(FORWARD)
})
```

```template
player.onChat("destroy", function () {
	
})
```
