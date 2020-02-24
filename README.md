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

Command to create a new react project, from https://reactjs.org/tutorial/tutorial.html#setup-for-the-tutorial

    $ cd <parent directory>
    $ npx create-react-app james-bond-react
    $ npm start
    
Command to deploy to github pages, from https://github.com/gitname/react-gh-pages
(once you've connected the github repo)

    $ npm install gh-pages --save-dev
    $ npm run deploy
