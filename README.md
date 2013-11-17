GMM-PIR
=======

<h3>Description</h3>

Described by <i>Chris Stauffer</i> and <i>W.E.L. Grimson</i> in their seminal paper, <a href=http://www.ai.mit.edu/projects/vsam/Publications/stauffer_cvpr98_track.pdf> "Adapative Background Mixture Models for Real-Time Tracking"</a>,
according to that paper, whenever new image data is derived, there's a recursive formula to get exponential moving statistics
for these parameters. In addition to the variables (which stand for standard deviation, incoming data vectors, covariance matrix
and parameters that manipulate the learning rate), you'll realize that the algorithm will assume large variances as the standard
and the most minute probabilities will be derived out of those functions, resulting in extremely slow convergence.


<h3>Purpose</h3>

This Gaussian mixture model will be used for background subtraction and updating the mean and covariance of the models.




************************************************************************

Permission to use, copy, modify and distribute this software and its
documentation for any purpose, and for a fee, is hereby granted on the
condition that the above copyright notice appear in all copies and that
both the copyright notice and this permission notice and warranty
disclaimer appear in supporting documentation, and that the name of
Desmond J. Watson not be used in advertising or publicity pertaining
to distribution of the software without specific written prior permission.

The owner of this software, Desmond J. Watson, disclaims all
warranties with regards to this software, including all implied
warranties of merchantability and fitness. In no event shall the owner
of this software, Desmond J. Watson, be liable for any special, indirect
or consequential damages or any damages whatsoever resulting from
loss of use, data or profits, whether in an action of contract, negligence
or other tortious action, arising out of or in, connection with the use or
performance of this software.

*****************************************************************************


<h3>© Copyright 2013 The Hexagon Lavish. All Rights Reserved.</h3>
