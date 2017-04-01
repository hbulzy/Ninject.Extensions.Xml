This extension allows users to create Ninject modules using XML and load them at runtime. Because XML is not a
programming language, these modules are naturally not as powerful as those defined using code.

An example of the syntax:

    <module name="SomeModule">
      <bind service="Game.IWeapon" to="Game.Sword"/>
      <bind service="Game.IWarrior" toProvider="Game.SamuraiProvider"/>
    </module>
    因为项目需要为 此项目 增加 属性注入能力
    
