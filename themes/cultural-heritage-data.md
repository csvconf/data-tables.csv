# Data Tables Theme: Cultural Heritage Data

Libraries, archives, museums, and other holders of cultural heritage
artifacts are releasing metadata (e.g. artist or author information,
medium, physical dimensions) about those artifacts in the open for
public reuse and analysis.  For the "Cultural Heritage Data" theme at
Data Tables, we want to explore these repositories of
"[cultural source code](https://labs.cooperhewitt.org/2012/releasing-collection-github/)"!

## Datasets

### Carnegie Museum of Art

The [collection data](http://collection.cmoa.org/collection-data/) of
the Carnegie Museum of Art in Pittsburgh, Pennsylvania provided as CSV
and JSON files uploaded to GitHub.  The datasets are described using a
`datapackage.json` file: [#22](../../../issues/22)

<https://github.com/cmoa/collection>

### The Metropolitan Museum of Art in New York.

The
[collection data](http://www.metmuseum.org/blogs/digital-underground/2017/open-access-at-the-met)
of The Metropolitan Museum of Art in New York: [#23](../../../issues/23)

<https://github.com/metmuseum/openaccess>

### The Tate Gallery

The
[collection data](http://www.tate.org.uk/about/our-work/digital/collection-data)
of Tate, a family of four galleries holding British art: [#24](../../../issues/24)

<https://github.com/tategallery/collection>

### Cooper Hewitt

The
[collection data](https://labs.cooperhewitt.org/2012/releasing-collection-github/)
of the Cooper Hewitt, Smithsonian Design Museum in New York: [#27](../../../issues/27)

<https://github.com/cooperhewitt/collection>

### Museum of Modern Art (MoMA)

The [collection data](https://medium.com/@foe/here-s-a-roundup-of-how-people-have-used-our-data-so-far-80862e4ce220) of the Museum of Modern Art (MoMA) in New York: [#28](../../../issues/28)

<https://github.com/MuseumofModernArt/collection>

## Interesting things that can be done

- Inspect the data and describe the schema if it doesn't yet exist
  - You can do this with a `datapackage.json`
    (<http://specs.frictionlessdata.io/data-package/>) or CSV on the
    Web metadata file (<http://w3c.github.io/csvw/>)
- Clean the data
  - As an example, Srini Kadamati explored the particular issues
    relevant to collection data and how they can be
    [cleaned with Python](http://www.dataquest.io/blog/data-cleaning-with-python/).
- Create an basic analysis
  - As an example, FiveThirtyEight's Oliver Roeder produced articles analyzing
[New York’s Metropolitan Museum of Art](http://fivethirtyeight.com/features/an-excavation-of-one-of-the-worlds-greatest-art-collections/) and the [MoMa](https://fivethirtyeight.com/features/a-nerds-guide-to-the-2229-paintings-at-moma/).
and yielded some interesting insights including:
    - Top 10 countries of origin for items in the collection
    - Top 10 categories of items in the collection by type and year of origin
    - Map year acquired to year painted as a measure of the rate of modernization
    - A focus on vases by year and civilization of origin
- Create a bot
  - As an example, [@NYPLEmoji]((https://twitter.com/nyplemoji) is a Twitter bot that receives emoji replies and responds with an image related to that emoji.

## Add context

- How do these collection datasets relate to each other?
- How is the same artist, location, medium, etc. represented across datasets?

## Open source platforms and tools

### Decentralized Web

Decentralized data storage systems, like InterPlanetary File System
(IPFS), are
[currently](https://github.com/ipfs/archives/issues/68#issuecomment-294160839)
[being](https://discuss.ipfs.io/t/whos-using-ipfs-in-libraries-archives-and-museums/130)
[explored](https://github.com/ipfs/community/issues/224>) as a way to
store and share cultural heritage data.

### Palladio

Palladio is a tool for
[visualizing complex historical data](http://hdlab.stanford.edu/palladio/).

### TimelineJS

TimelineJS is a tool for
[building interactive timelines](http://timeline.knightlab.com/).

## Other Resources

### Collections as Data

If you are interested in
"[Collections as Data](https://collectionsasdata.github.io/)", there
is a working group aimed at developing a strategic approach to sharing
and describing such datasets.
