Collects entities from multiple source directories and builds the Entity Manifest File for Deployment.

# Introduction

ManifestGenerator collects entities from multiple source directories and builds the Entity Manifest File for Deployment.


# Details

```
1. <target name="generate_entity_manifest">
2.  <generatemanifest manifestType="entityName" manifestFileName="${entity.manifest}">
3.   <fileset dir="GameInfo" includes="*.entity"/>
4.   <fileset dir="${sins.installation.dir}/GameInfo" includes="*.entity" excludes="*AntiMatterRestore.entity,*EvasiveManeuvers.entity"/>
5.   <fileset dir="${entrenchment.installation.dir}/GameInfo" includes="*.entity"/>
6.  </generatemanifest>
7. </target>
8. 
9. <target name="generate_brush_manifest">
10.  <generatemanifest manifestType="brushFile" manifestFileName="${brush.manifest}">
11.   <fileset dir="Window" includes="*.brushes"/>
12.   <fileset dir="${sins.installation.dir}/Window" includes="*.brushes"/>
13.   <fileset dir="${entrenchment.installation.dir}/Window" includes="*.brushes"/>
14.  </generatemanifest>
15. </target>
```