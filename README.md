# react-cheatsheet

https://reactjs.org/tutorial/tutorial.html

To create a component, use:

    function Board(props) {
      return (<div>);
    }

or

    function Board(props) {
      return AnotherComponent();
    }

or

    class Board extends React.Component {
      constructor(props) {
        super(props);
        this.state = {};
        this.handleClick = this.handleClick.bind(this);
      }
      handleClick() {
        this.setState(...);
      }
      render() {
        return (<div>);
      }
    }

Either use a function or a class.  Use a class if you want helper methods or state.  

https://reactjs.org/docs/state-and-lifecycle.html
https://reactjs.org/docs/react-component.html

Command to create a new react project:

    $ cd <parent directory>
    From https://reactjs.org/tutorial/tutorial.html#setup-for-the-tutorial
    $ npx create-react-app james-bond-react
    From https://github.com/gitname/react-gh-pages
    $ npm install gh-pages --save-dev
    $ npm start

