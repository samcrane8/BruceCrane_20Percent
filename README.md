BruceCrane_20Percent
====================

My twenty percent repository.

I really liked that engarde project. So much in fact, I think I'll make my project an extension of that.

When I was first learning about programming, I thought it would be pretty cool to have a robot play against you.


Specifics of this project:
  -- I want a console based game that can be played with as many robot AI's or human AI's as you want.
  -- I want the robots to have independent threads that consider possibilities simultaneously.
  -- Alpha-beta pruning
  -- Optimization with creating nodes:
      -- for example, after a move is made, each AI should trim any part of the possibility tree that didn't occur,
         but then keep the rest of the tree and keep on considering possibilities. 
        -- I'm going to have to check if this is a viable option, and check some code where it's been implemented.
  -- I want to have a good valuing heuristic. I think that's where my bot failed (and some bug I've yet to understand).
