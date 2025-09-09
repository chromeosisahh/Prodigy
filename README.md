# Prodigy
I've seen a lot of script's for prodigy having, obfuscation which they don't need i'm gonna provide the unobfuscated version stay safe use ur brain


```javascript
Boot.prototype.game['_state']['_current'].user.source.hasMembership =
  function () {
    return true
  }

```javascript
var u_prompt = prompt('What do you want your walkspeed to be?')
null === u_prompt
  ? alert('Not a valid answer.')
  : ((u_prompt = parseFloat(u_prompt)),
    (Boot.prototype.game['_state']['_current'].user.walkSpeed = u_prompt))
