This code is distributed as is without warranty.  If you use this
for your research, please cite:

Learning deformable shape manifolds,
Samuel Rivera and Aleix M. Martinez, Pattern Recognition.
Volume 45, Issue 4, April 2012, Pages 1792-1801


See 'example.m'  for an example.

It basically sets up the parameters and calls 'mainDSREyeCenter.m'

This code assumes the objects are aligned in rotation.  If you would like to rotate
 the objects, you should detect the reference positions (eye positions for face) 
and rotate the images, then run the detector again on the whole face.


%   Copyright (C) 2009, 2010, 2011 Samuel Rivera, Liya Ding, Onur Hamsici, Paulo
%   Gotardo, Fabian Benitez-Quiroz and the Computational Biology and 
%   Cognitive Science Lab (CBCSL).
% 
% Contact: Samuel Rivera (sriveravi@gmail.com)
