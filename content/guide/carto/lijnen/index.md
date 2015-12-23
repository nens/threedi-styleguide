+++
date = "2015-10-30T11:56:34+01:00"
draft = false
title = "Lijnen"

+++

Lijnsymbologie
--------------



| Naam / Klasse     | Zichtbaarheid         | Status            | Stroming              | Onderscheid       | |
|-----------------	|---------------------	|-----------------	|-------------------	|------------------	|---------------------------|
| <a href="#channel">Channel</a>         	| bevat zoom_category 	| open/afgesloten 	| debiet + snelheid 	| Oppervlaktewater 	|
| <a href="#pipe">Pipe</a>            	| bevat zoom_category 	| open/afgesloten 	| debiet + snelheid 	| Riolering        	|
| <a href="#pumpstation">Pumpstation</a>     	| bevat zoom_category 	| staat aan/uit   	| debiet            	| Opp of riolering 	|
| <a href="#weir">Weir</a>            	| bevat zoom_category 	| open/afgesloten 	| debiet + snelheid 	| Opp of riolering 	|
| <a href="#culvert">Culvert</a>         	| bevat zoom_category 	| open/afgesloten 	| debiet + snelheid 	| Oppervlaktewater 	|
| <a href="#orifice">Orifice</a>         	| bevat zoom_category 	| open/afgesloten 	| debiet + snelheid 	| Opp of riolering 	|
| <a href="#levee">Levee</a>           	| toggle visibility   	| -                	| -                 	| Oppervlaktewater 	|
| <a href="#obstacle">Obstacle</a>        	| toggle visibility   	| -                	| -                 	| geen             	|
| <a href="#bound2d">2D Boundary</a>    	| toggle visibility   	| -                	| -                 	| geen             	|



## <a name="channel"></a>Channel

> An open conduit either naturally or artificially created which periodically or continuously contains moving water, or which forms a connecting link between two bodies of water.

<div class="panel panel-default">
  <div class="panel-heading">
    <h3 class="panel-title">DWA Channel <span class="badge pull-right">Z14+</span></h3>
  </div>
  <div class="panel-body">
    <p>Wordt gebruikt voor droogweerafvoerkanalen. Geeft richting aan met driehoeken en/of bolletjesanimatie.</p>
    <ul class="list-group">
      <li class="list-group-item"><img src="../../../images/ui/linestyle-dwa.png" /></li>
    </ul>
  </div>
</div>

<div class="panel panel-default">
  <div class="panel-heading">
    <h3 class="panel-title">RWA Channel <span class="badge pull-right">Z14+</span></h3>
  </div>
  <div class="panel-body">
    <p>Wordt gebruikt voor regenweerafvoer. Geeft richting aan met driehoeken en/of bolletjesanimatie.</p>
    <ul class="list-group">
      <li class="list-group-item"><img src="../../../images/ui/linestyle-rwa.png" /></li>
    </ul>    
  </div>
</div>

<div class="panel panel-default">
  <div class="panel-heading">
    <h3 class="panel-title">Mixed Channel <span class="badge pull-right">Z14+</span></h3>
  </div>
  <div class="panel-body">
    <p>Wordt gebruikt voor gemengde stelsels. Geeft richting aan met driehoeken en/of bolletjesanimatie.</p>
    <ul class="list-group">
      <li class="list-group-item"><img src="../../../images/ui/linestyle-mixed.png" /></li>
    </ul>    
  </div>
</div>

## <a name="pipe"></a>Pipe

> A tube used to convey water, gas, oil, or other fluid substances.

<div class="panel panel-default">
  <div class="panel-heading">
    <h3 class="panel-title">Pipe <span class="badge pull-right">Z15+</span></h3>
  </div>
  <div class="panel-body">
    <p>Wordt gebruikt voor reguliere leidingen. Geeft richting aan met driehoeken en/of bolletjesanimatie.</p>
    <ul class="list-group">
      <li class="list-group-item"><img src="../../../images/ui/linestyle-pipe.png" /></li>
    </ul>
  </div>
</div>

<div class="panel panel-default">
  <div class="panel-heading">
    <h3 class="panel-title">Pressure pipe <span class="badge pull-right">Z15+</span></h3>
  </div>
  <div class="panel-body">
    <p>Wordt gebruikt voor drukleidingen. Geeft richting aan met driehoeken en/of bolletjesanimatie.</p>
    <ul class="list-group">
      <li class="list-group-item"><img src="../../../images/ui/linestyle-pressure-pipe.png" /></li>
    </ul>
  </div>
</div>


## <a name="pumpstation"></a>Pumpstation

> A pump station mechanically lifts storm water runoff from a gravity fed collection cistern to a discharge place or outfall.

<div class="panel panel-default">
  <div class="panel-heading">
    <h3 class="panel-title">Pumpstation I <span class="badge pull-right">Z14+</span></h3>
  </div>
  <div class="panel-body">
    <ul class="list-group">
      <li class="list-group-item"><img src="../../../images/ui/icon-pumpstation.png" class="icon-1x" /></li>
      <li class="list-group-item"><img src="../../../images/ui/icon-pumpstation.png" class="icon-2x" /></li>
      <li class="list-group-item"><img src="../../../images/ui/icon-pumpstation.png" class="icon-3x" /></li>
    </ul>
  </div>
</div>

<div class="panel panel-default">
  <div class="panel-heading">
    <h3 class="panel-title">Pumpstation II (Lizard) <span class="badge pull-right">Z15+</span></h3>
  </div>
  <div class="panel-body">
    <ul class="list-group">
      <li class="list-group-item"><img src="../../../images/ui/icon-pumpstation-ii.png" class="icon-1x" /></li>
      <li class="list-group-item"><img src="../../../images/ui/icon-pumpstation-ii.png" class="icon-2x" /></li>
      <li class="list-group-item"><img src="../../../images/ui/icon-pumpstation-ii.png" class="icon-3x" /></li>
    </ul>    
  </div>
</div>


## <a name="weir"></a>Weir

> A weir is a barrier across a river designed to alter its flow characteristics.

<div class="panel panel-default">
  <div class="panel-heading">
    <h3 class="panel-title">Weir <span class="badge pull-right">Z16+</span></h3>
  </div>
  <div class="panel-body">
    <ul class="list-group">
      <li class="list-group-item"><img src="../../../images/ui/icon-weir.png" class="icon-1x" /></li>
      <li class="list-group-item"><img src="../../../images/ui/icon-weir.png" class="icon-2x" /></li>
      <li class="list-group-item"><img src="../../../images/ui/icon-weir.png" class="icon-3x" /></li>
    </ul>
  </div>
</div>


## <a name="culvert"></a>Culvert

> A tunnel carrying a stream or open drain under a road or railway.

<div class="panel panel-default">
  <div class="panel-heading">
    <h3 class="panel-title">Culvert <span class="badge pull-right">Z16+</span></h3>
  </div>
  <div class="panel-body">
    <ul class="list-group">
      <li class="list-group-item"><img src="../../../images/ui/icon-culvert.png" class="icon-1x" /></li>
      <li class="list-group-item"><img src="../../../images/ui/icon-culvert.png" class="icon-2x" /></li>
      <li class="list-group-item"><img src="../../../images/ui/icon-culvert.png" class="icon-3x" /></li>
    </ul>
  </div>
</div>


## <a name="orifice"></a>Orifice

> An orifice is an opening through which flow occurs.

<div class="panel panel-default">
  <div class="panel-heading">
    <h3 class="panel-title">Orifice <span class="badge pull-right">Z17+</span></h3>
  </div>
  <div class="panel-body">
    <ul class="list-group">
      <li class="list-group-item"><img src="../../../images/ui/icon-orifice.png" class="icon-1x" /></li>
      <li class="list-group-item"><img src="../../../images/ui/icon-orifice.png" class="icon-2x" /></li>
      <li class="list-group-item"><img src="../../../images/ui/icon-orifice.png" class="icon-3x" /></li>
    </ul>
  </div>
  <div class="panel-body">
    <ul class="list-group">
      <li class="list-group-item"><img src="../../../images/ui/icon-orifice-ii.png" class="icon-1x" /></li>
      <li class="list-group-item"><img src="../../../images/ui/icon-orifice-ii.png" class="icon-2x" /></li>
      <li class="list-group-item"><img src="../../../images/ui/icon-orifice-ii.png" class="icon-3x" /></li>
    </ul>
  </div>  
</div>



## <a name="levee"></a>Levee

> A natural or manmade earthen barrier along the edge of a stream, lake, or river.

<div class="panel panel-default">
  <div class="panel-heading">
    <h3 class="panel-title">Levee <span class="badge pull-right">Z14+</span></h3>
  </div>
  <div class="panel-body">
    <ul class="list-group">
      <li class="list-group-item"><img src="../../../images/ui/linestyle-levee.png" /></li>
    </ul>
  </div>
</div>

## <a name="obstacle"></a>Obstacle

> Something that blocks access (to fluids in this case).

<div class="panel panel-default">
  <div class="panel-heading">
    <h3 class="panel-title">Obstacle</h3>
  </div>
  <div class="panel-body">
    <ul class="list-group">
      <li class="list-group-item"><img src="../../../images/ui/linestyle-obstacle.png" /></li>
    </ul>
  </div>
</div>


## <a name="bound2d"></a>2D Boundary

> Used to define the location of a flow-time boundary point within a 2D Simulation

<div class="panel panel-default">
  <div class="panel-heading">
    <h3 class="panel-title">2D Boundary</h3>
  </div>
  <div class="panel-body">
    <ul class="list-group">
      <li class="list-group-item"><img src="../../../images/ui/linestyle-2d-boundary.png" /></li>
    </ul>
  </div>
</div>
