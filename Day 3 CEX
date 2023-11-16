import React from "react";
import { useState } from "react";
function ToggleMessage()
{
    const [Msg , setMsg] = useState(false)
    function Change()
    {
        setMsg(!Msg)
    }
    return(
        <div>
        <button onClick={Change}>
            {Msg ? 'Hide Component' : 'Show Component'}
        </button>
            {Msg && <h2><i>Hi! How are You!!!</i></h2>}
        </div>
    )
}
export default ToggleMessage;
