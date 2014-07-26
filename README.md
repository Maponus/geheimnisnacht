Warhammer Geheimnishnacht
===============


# ROADMAP

we start here



* [ ] 0.1.0 *basic -- means getting rid of non warhammer stuff*
  - [x] basic port of cbs 
  - [ ] port council conected data, and events
  - [ ] basic port of factions
  - [ ] basic port of objectives
  - [ ] basic port of on_action mechanics with corresponding events
  - [ ] basic port of decisions
  - [x] traits
  - [x] modifiers
  - [x] history
  - [x] titles

* [ ] 0.1.1 
  - [ ] move to backup all static data for non-completed systems 
  - [ ] move to backup all common data belonging to non-human races
  - [ ] move to backup all history data belonging to non-human races
  - [ ] port all events from events_to_port, basic port only - get rid of non warhammer stuff


* [ ] 0.1.2 
  - [ ] implement buildings for all human races 
  - [ ] implement units, retinues and culture modifires (humans only)
  - [ ] final touch of traits, modifiers, cultures, religions (humans only)


* [ ] 0.1.3
  - [ ] make race&culture specific changes to basic events (humans only)
  - [ ] make race&culture specific localisation chagnes (humans only)

* [ ] 0.1.4
  - [ ] implement chaos connected event based mechanics
  - [ ] implement doom engine
  - [ ] implement magic learning & inheritance mechanics
  - [ ] implement arcane magic for characters (fire, ice, chaos)

* [ ] 0.1.5
  - [ ] implement arcane magic for battlefield & council
  - [ ] implement full duel engine
  - [ ] implement beastmean engine

* [ ] 0.1.6
  - [ ] expand amount of lores (fire, ligt, ice, chaos, lady of the lake lores...?)
  - [ ] hidden chaos mechancis (cults )
  - [ ] make necessary event,plots, actions modifications to integrate warhammer new systems into other game mechancis

* [ ] 0.1.7
  - [ ] finish all the province info for old world
  - [ ] finish off the map visuals
  - [ ] make culutre spcific portraits (humans)
  - [ ] make culture specific clothes (humans)

* [ ] 0.1.8
  - [ ] make culture specific unti graphics (humans)
  - [ ] make culture specific buildings (humans)
  - [ ] graphical culture changes
  - [ ] make culture specific untit graphics (humans)
  - [ ] make all humans interface additions

* [ ] 0.1.9 
  - [ ] flavour and historic events (just a few for humans only)
  - [ ] bug fixing
  - [ ] balancing
  - [ ] localisation final touches

* [ ] 0.2.0 *First playable immersive versions with humans*
  - norscans, imperials, bertonnians, hungs, kurgans, kislevites, border guys ready 
  - warhammer specific systems (magic, chaos cultists, doom engine, beastmen, duels)
  - warhammer changed vanilla mechanics




# LIST OF TOPICS IN GENERAL
1. Prepare static structures of mod:
  - traits
  - modifiers (static, opinion modifiers)
  - fill history files
  - buildings
  - retinues
  - cultures
  - religions
  - titles
  - objectives
  - factions
  - diseases
  - troops

2. Code most basic mechanisms:
  - CBs
  - diplomatic actions
  - councill stuff
  - objectives
  - factions
  - plot

3. Port the basic event code to warhammer:
  - character personal events			
  - religious events				
  - civil war events				
  - on_action_events				  
  - friends rivals event			
  - childchood events
  - tons of other

4. Implement warhammer specific systems:
  - doom engine
  - chaos invasions
  - chaos cults
  - falling to chaos 
  - duels
  - magic
  - beastman system
  - objectives
  - historical and flavour events

5. Late bate features
  - bugfixing 
  - localisation
  - balancing
  - portraits
  - flags
  - units
  - event pics
  - interface changes



# Task propositions for team members

**Shade:**
- complete the map
- prepare an culture/religion specific things for factions
- prepare an culture/religion specific things for council 
- think about names for council positions for human races
- debug the history files & provinces
- implement building for all human races on northern hemisphere (all except arabyans?)
- work on event pictures that are placeholders now (check gfx directory of mod)

**Illathid:**
- get reference on stats of typical armies of human races used in mod
- write description for all human religions and chaos ones
- think about names for council positions for human races
- prepare an culture/religion specific things for factions
- prepare an culture/religion specific things for council 
- obtain a reference images on the look of units from all dlcs

**Others:**
Who else we have?

# Coding guide
- use four space indentation in dynamic script code
- see docs directory 
