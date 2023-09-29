# video_sychronazation
Master Thesis

In the experiments, two different methods were tested in an attempt to align frame0 and frame1 from videos captured from two different perspectives.
(1)loFTR +  background mask + sampon distance(scaler)
(2)dense matching +  background mask + sampon distance(scaler)
But as we can see the results in the last cell,they are not working well.I think they only work properly if all three conditions are met:
1.There must be enough matching points in both frames.
2.The matching points must be detected and moving, but not leaving the bounding box.
3.The time slot must be large enough.
4.Also, the movement should not be repeated.
which were unrealistic, so i move forward to optical flow...

