# What goes into the Expo SDK?

The simplest way to look at Expo's SDK is to think of it as a toolbox that Expo provides. Included in that toolbox are what we believe are the most essential and widely usable tools for building extraordinary and powerful apps (like a hammer, powerdrill, and saw). You can do a lot with just these tools and creative thinking. Of course, there are other tools out there that are made for narrower use-cases (like a [tailpipe cutter](https://www.amazon.com/OEMTOOLS-27045-Tailpipe-Cutter/dp/B004FELJ20)). These can be really useful, and sometimes are even make-or-break for specific apps.

We can't include each and every native module out there because that would make for an extremely heavy toolbox (i.e. large [binary size](http://expo.fyi/managed-app-size) and maintenance cost). Instead, we only include native modules that we believe satisfy a wide range of needs for a large majority of developers. If you need a specific tool that isn't provided in the Expo toolbox, then you can always use the [bare workflow](https://docs.expo.io/workflow/customizing/) and add any native module you'd like to your project, while still enjoying most of the benefits that Expo provides.

If you think there is a module that _does_ satisfy a wide range of needs for a majority of developers and isn't in the SDK yet, then we encourage you to open a feature request on our [Canny](https://expo.canny.io/feature-requests) so that we might include that module in the future!