# License Policy
The license of any external artifact (open-source or commercial) must be examined before introducing
that external artifact into organization assets.  The examination must determine the cost of compliance
with terms of the license and any impairment to proprietary artifact.

## Purpose
Intellectual properties are key assets of an organization.  
Every development group should protect its intellectual property and respect the intellectual property of others.

## Procedures
This policy applies to all licensed artifacts, regardless of the method of procurement.  Downloadable
artifact requires the same level of review as artifacts acquired from commercial sources in a formal
contracting process.

- Employees must not use intellectual property from prior employers or engagements.
- Employees must not use non-organization intellectual property covered by a non-disclosure agreement.

## Discussion
Common uses of Open Source

### Tools
Tools are artifact which is not repackaged in a organization product but may be used to create organization products.
Integrated development environments (IDEs) and editors, compilers, documentation tools, web servers, 
virtual machine engines, and more are tools. An open source compliant license places no restriction
on how the tool is used, for business or personal purposes.

### Binary Dependency
A Binary Dependency is software which is repackaged in a product without modification. Libraries,
frameworks, and components are often binary dependencies.  Care must be exercised on license restrictions.
Some licenses restrict use with proprietary software.

### Source Dependency
A Source Dependency is software which is repackaged in a product with source modification. Extra care
must be exercised with examining license restrictions.  Some licenses would cause us to publish the
modifications and the source code of all dependent work.

### Typical Open Source Licenses
The [Open Source Initiative](https://opensource.org/licenses) evaluates and categorizes open source licenses.  A further classification
of OSI’s Licenses that are popular, widely used, or with strong communities from most restrictive to
least restrictive is: viral, dynamic linking, permissive.

#### Viral
Viral licenses require the use of a viral license by any derived or dependent work.  Viral licenses 
usually require source code disclosure of any derived works.  Dependency use of this class of license
is extremely damaging to users’ intellectual property.

#### Dynamic Linking
Dynamic linking licenses are viral licenses with an exception for proprietary software to use the
software as delivered.  Source Dependency use of this class of license may impair users’ intellectual property.

#### Permissive
Permissive licenses allow the use of the licensed artifact for any purpose or use.  Users of the 
artifact assume any liability resulting from the use of that artifact.

### Reviewed Licenses
In the following table, reviewed licenses are marked as being acceptable (✓) or not acceptable (✗) for common uses based upon their virality.

|         | Tools | Binary | Source |                                
| ------: | :---: | :----: | :----: |
| [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0) | ✓ | ✓ | ✓ |
| [BSD "New" or "Revised" license](https://en.wikipedia.org/wiki/BSD_licenses#3-clause_license_(%22BSD_License_2.0%22,_%22Revised_BSD_License%22,_%22New_BSD_License%22,_or_%22Modified_BSD_License%22)) | ✓ | ✓ | ✓ |
| ["FreeBSD" license](https://en.wikipedia.org/wiki/BSD_licenses#2-clause_license_(%22Simplified_BSD_License%22_or_%22FreeBSD_License%22)) | ✓ | ✓ | ✓ |
| [Common Development and Distribution License](https://en.wikipedia.org/wiki/Common_Development_and_Distribution_License) | ✓ | ✓ | ✓ |
| [Eclipse Public License](https://www.eclipse.org/legal/epl-v10.html) | ✓ | ✓ | ✓ |
| [GNU General Public License](https://www.gnu.org/licenses/gpl-3.0.en.html) | ✓ | ✗ | ✗ |
| [GNU Affero General Public License](https://www.gnu.org/licenses/agpl-3.0.en.html) | ✓ | ✗ | ✗ |
| ["Lesser" General Public License](https://www.gnu.org/licenses/lgpl-3.0.en.html) | ✓ | ✓ | ✗ |
| [MIT license](https://en.wikipedia.org/wiki/MIT_License) | ✓ | ✓ | ✓ |
| [Mozilla Public License 2.0](https://www.mozilla.org/en-US/MPL/2.0/) | ✓ | ✓ | ✓ |
| [Oracle Binary Code License](http://www.oracle.com/technetwork/java/javase/terms/license/index.html) | ✓ | ✓ | ✗ |
| No explicit license | ✗ | ✗ | ✗ |

### Artifacts Without an Explicit License
Artifacts without an explicit licence or release grant is implicitly copyrighted material.  Artifacts without license cannot be used.

<p align="center">
  <a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png"/></a>
  <br />
  This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
</p>
