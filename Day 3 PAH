import {useState} from 'react'
function Mine()
{
  const [transformationState , setransformationState] = useState(false)
  function Change()
  {
    setransformationState(!transformationState)
  }
  return(
    <div>
    <button onClick={Change}>ClickMe</button>
    {transformationState ? <h3><i>SuperSaiyan</i></h3> : <h3><i>Kaioken</i></h3>}
    </div>

  )
}
export default Mine;
