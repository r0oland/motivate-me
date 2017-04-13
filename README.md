# motivate_me
Print motivational quotes to the Matlab command line to inspire your worker bees!

Quotes can easily be added to the text file quotes.txt with every quote
entered as a string without line breaks (see quotes.txt file).

I use this function in my startup.m file to show a quote when Matlab starts.

### Examples
```Matlab
motivate_me; % display quote on command line
motivate_me(5); % display quote five on command line:
  Always get plenty of sleep, if you can.
motivate_me(5,true); % display quote, with lines above an below
------------------------------------------------------------------
  Always get plenty of sleep, if you can.
------------------------------------------------------------------
```

## Sources
I gathered inspirational quotes from the following places:
- Messages from your friends at Slack
- http://theoatmeal.com/
- http://www.curatedquotes.com/inspirational-quotes/funny/
- http://www.smosh.com/smosh-pit/photos/20-worst-motivational-posters
- http://www.despair.com

I also reused a small portion of the code originally found in cprintf(), programmed by Yair M. Altman [[link]](https://www.mathworks.com/matlabcentral/fileexchange/24093-cprintf-display-formatted-colored-text-in-the-command-window)

Johannes Rebling (johannesrebling@gmail.com), IBMI 2017
