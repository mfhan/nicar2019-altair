# Data Visualization With Altair
*Code and resources originally from a NICAR 2019 session; last updated March 2020.*

#### How to install
Fork or clone this repo to your computer. Make sure you have Python 3 and [Pipenv](LINK) installed on your computer.

Open this folder in your terminal and run `pipenv install`. This may take a few minutes — among other things, it will install Pandas, Numpy, Jupyter, Jupyter Lab and, of course, Altair.

Once that's done, run `pipenv shell` and then `jupyter lab`. This should open up in your browser.

*(Note: You should also be able to run this with the `jupyter notebook` command; `jupyter lab` is the next generation of Jupyter, though, and gives you some additional options, like a file-management interface and the ability to have multiple files open in different panes at the same time.)*

#### Exploring the data
The project data is in the `data` directory. You can open the files right inside Jupyter Lab and check out how they're structured, or load them into your notebook with Pandas; the data definitions and sources are listed in that directory's readme.

#### Running the code
Open up the `fun-with-altair.ipynb` file. That's your working file; it's got all the libraries you'll need, the dataset imports and the prompts for what you'll do each step of the way. Run cells by hitting `shift-enter`. Try to follow the prompts by looking at the Altair documentation and Googling. If you get stuck, I give you permission to open the `fun-with-altair-SOLUTIONS.ipynb` notebook and peek, but try to make the charts before you do that!


#### Other resources
- Link to this repo: [bit.ly/nicar2019-altair-code](http://bit.ly/nicar2019-altair-code)
- Link to the session slides: [bit.ly/nicar2019-altair-slides](http://bit.ly/nicar2019-altair-slides)
- Check out the [Altair documentation](https://altair-viz.github.io/)
- For more about the technology underneath Altair, here's the [Vega-Lite documentation](https://vega.github.io/vega-lite/docs/)
- If you're ready to dive into more complex uses of Altair, this [PyCon Altair Tutorial](https://github.com/altair-viz/altair-tutorial/blob/master/notebooks/Index.ipynb) is a good place to start
- Here's how you can [use Altair/Vega code with Flourish](https://flourish.studio/2018/05/29/vega-lite-in-flourish/) for a quick, embeddable interactive