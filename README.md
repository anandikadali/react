# react
import React, { Component } from 'react';
import Display from './Display';
class App extends Component {
    state={
        name:'Telugu'
    }
    render() {
        return (
            <div>
               <Display name={this.state.name}/> 
            </div>
        );
    }
}

export default App;
import React, { Component } from 'react';

class Display extends Component {
    render() {
        return (
            <div>
                <h2>{this.props.name}</h2>
            </div>
        );
    }
}

export default Display;
