---
title: class mip PolicyEngine Settings 
description: Reference for class mip PolicyEngine Settings 
author: BryanLa
ms.service: information-protection
ms.topic: reference
ms.date: 09/27/2018
ms.author: bryanla
---
# class mip::PolicyEngine::Settings 
Defines the settings associated with a [PolicyEngine](class_mip_policyengine.md).
  
## Summary
 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
 public Settings(const std::string& engineId, const std::string& clientData, const std::string& locale)  |  [PolicyEngine::Settings](class_mip_policyengine_settings.md) constructor for loading an existing engine.
 public Settings(const Identity& identity, const std::string& clientData, const std::string& locale)  |  [PolicyEngine::Settings](class_mip_policyengine_settings.md) constructor for creating a new engine.
 public const std::string& GetEngineId() const  |  Get the engine ID.
 public void SetEngineId(const std::string& id)  |  Set the engine ID.
 public const Identity& GetIdentity() const  |  Get the Identity object.
 public void SetIdentity(const Identity& identity)  |  Set the Identity object.
 public const std::string& GetClientData() const  |  Get the Client Data set in the settings.
 public void SetClientData(const std::string& clientData)  |  Set the Client Data string.
 public const std::string& GetLocale() const  |  Get the Locale set in the settings.
public void SetCustomSettings(const std::vector<std::pair<std::string, std::string>>& customSettings)  |  Set the custom settings, used for feature gating and testing.
public const std::vector<std::pair<std::string, std::string>>& GetCustomSettings() const  |  Get the custom settings, used for feature gating and testing.
 public void SetSessionId(const std::string& sessionId)  |  Set the session ID, used for client defined telemetry.
 public const std::string& GetSessionId() const  |  Get the session ID, a unique identifier.
  
## Members
  
### Settings
[PolicyEngine::Settings](class_mip_policyengine_settings.md) constructor for loading an existing engine.

Parameters:  
* **engineId**: Set it to the unique engine ID generated by AddEngineAsync or one self-generated. When loading an existing engine, reuse the ID else a new engine will be created. 


* **clientData**: customizable client data that can be stored with the engine when unloaded, can be retrieved from a loaded engine. 


* **locale**: engine localizable output will be provided in this locale.


  
### Settings
[PolicyEngine::Settings](class_mip_policyengine_settings.md) constructor for creating a new engine.

Parameters:  
* **identity**: Identity info of the user associated with the new engine. 


* **clientData**: customizable client data that can be stored with the engine when unloaded, can be retrieved from a loaded engine. 


* **locale**: engine localizable output will be provided in this locale.


  
### GetEngineId
Get the engine ID.

  
**Returns**: A unique string identifying the engine.
  
### SetEngineId
Set the engine ID.

Parameters:  
* **id**: engine ID.


  
### GetIdentity
Get the Identity object.

  
**Returns**: A reference to the identity in the settings object. 
  
**See also**: mip::Identity
  
### SetIdentity
Set the Identity object.

Parameters:  
* **identity**: the unique identity of a user. 


  
**See also**: mip::Identity
  
### GetClientData
Get the Client Data set in the settings.

  
**Returns**: A string of data specified by the client.
  
### SetClientData
Set the Client Data string.

Parameters:  
* **clientData**: user specified data.


  
### GetLocale
Get the Locale set in the settings.

  
**Returns**: The locale.
  
### SetCustomSettings
Set the custom settings, used for feature gating and testing.

Parameters:  
* **customSettings**: List of name/value pairs.


  
### GetCustomSettings
Get the custom settings, used for feature gating and testing.

  
**Returns**: List of name/value pairs.
  
### SetSessionId
Set the session ID, used for client defined telemetry.

Parameters:  
* **sessionId**: a unique string that connects telemetry events.


  
### GetSessionId
Get the session ID, a unique identifier.

  
**Returns**: The session ID.