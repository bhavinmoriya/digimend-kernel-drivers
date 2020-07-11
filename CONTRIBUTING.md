Hi Guys,

I have recently bought XP Pen G960. I did not see any driver for my tablet. So I followed
what has been suggested on your site and tried to experiment analogous stuff. Fortunately, it all went well
and I am using it now finally, working quite well. Thought of sharing with the community.

Here is the way you can make XP Pen G960 work on your Ubuntu 18.04,
\begin{enumerate}
\item cd /usr/share/X11/xorg.conf.d

\item ls

\item You might have a file with a name like "*wacom.conf"

\item sudo nano *wacom.conf
\item Copy the following and then paste it in the *wacom.conf (which you opened in previous stap)

Now, we save this in the following way,
\begin{enumerate}
\item ctrl O
\item Enter
\item yes
\end{enumerate}

\item restart the system 
\item Bingo!
\end{enumerate}
