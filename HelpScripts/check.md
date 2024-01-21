## check
Print a script's logs to Terminal
  
**Signature:**

  
```typescript

check [script] [args...]

```

  

## Parameters

  
- `check`: check log on script still running.
- `script`:  name script .
- `args`: These values provide additional information or parameters that the program can use to modify its behavior or perform specific actions.


**Example:**


  
```typescript

check hack.js MainScript

```

  
**Result:**
Checking log running on script hack.js

```Terminal
  
hack: Executing on 'iron-gym' in 1 minute 48.742 seconds (t=4,800)
hack: Successfully hacked 'iron-gym' for $0.000 and 16.885k exp (t=4,800) 
hack: Executing on 'zer0' in 1 minute 16.252 seconds (t=4,800)
hack: Failed to hack 'zer0'. Gained 14.775k exp (t=4,800)
hack: Executing on 'neo-net' in 59.668 seconds (t=4,800)
hack: Successfully hacked 'neo-net' for $0.000 and 14.775k exp (t=4,800)
hack: Executing on 'omega-net' in 3 minutes 33.453 seconds (t=4,800)
hack: Failed to hack 'omega-net'. Gained 15.619k exp (t=4,800)
hack: Executing on 'johnson-ortho' in 8 minutes 43.148 seconds (t=4,800)
hack: Failed to hack 'johnson-ortho'. Gained 31.238k exp (t=4,800)
hack: Executing on 'crush-fitness' in 5 minutes 59.200 seconds (t=4,800)
hack: Failed to hack 'crush-fitness'. Gained 21.951k exp (t=4,800)
hack: Executing on 'CSEC' in 28.219 seconds (t=4,800)
hack: Successfully hacked 'CSEC' for $0.000 and 4.643k exp (t=4,800)
hack: Executing on 'silver-helix' in 2 minutes 45.102 seconds (t=4,800) 
hack: Successfully hacked 'silver-helix' for $0.000 and 16.885k exp (t=4,800)
hack: Executing on 'phantasy' in 1 minute 29.021 seconds (t=4,800)
hack: Failed to hack 'phantasy'. Gained 12.664k exp (t=4,800)
hack: Executing on 'the-hub' in 6 minutes 0.227 seconds (t=4,800)

```


