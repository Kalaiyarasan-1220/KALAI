function Basic()
{
    const handlesubmit = (e) => {
        e.preventDefault();
        console.log(e.target.Name.value);
        console.log(e.target.email.value);
        console.log(e.target.feedback.value);
    }
    return(
        <div>
            <h1 >Basic form</h1>
            <hr/>
            <form onSubmit={handlesubmit}>
            <lable>
                Name:
                <input type="text" id="Name" placeholder="Enter your Name" />
            </lable><br/>
            <lable>
                Email:
                <input type="email" id="email" placeholder="Enter your Email"/>
            </lable><br/>
            <label>
                Message:
                <textarea id="feedback" placeholder="Enter your feedback" row={12} column={15}/>
            </label><br/>
            <button type="Submit">Submit</button>
            </form>

        </div>
    )
}

export default Basic;
