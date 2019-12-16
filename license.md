# License Policy
The license of any external artifact (open-source or commercial) must be examined before introducing
that external artifact into organization assets.  The examination must determine the cost of compliance
with terms of the license and any impairment to proprietary artifact.

## Purpose
Intellectual properties are key assets of an organization.  Every development group should protect
its intellectual property and respect the intellectual property of others.

## Procedures
This policy applies to all licensed artifacts, regardless of the method of procurement.  Downloadable
artifact requires the same level of review as artifacts acquired from commercial sources in a formal
contracting process.

- Employees must not use intellectual property from prior employers or engagements.
- Employees must not use non-organization intellectual property covered by a non-disclosure agreement.

## Discussion
Common uses of Open Source.  Many open source licenses have restrictions on the use of the licensed
artifact:
                          
- Some licenses restrict use with proprietary software. 
- Some licenses require publication of any modifications and the source code of all derived work.
- Some licenses create exceptions for use of libraries.

### Usage Types

#### Conveyance
Any transfer of an artifact that enables others to make a copy of that artifact.  Transferring any
artifacts to an on-premise device is conveyance.  Any artifact running inside a web browser or email
client are also conveyed artifacts.

#### Linked
Linked usage occurs when artifacts are combined into the product at runtime.  This includes classes
linked from the classpath or shared objects from a dynamic library.

#### Network
Network usage clauses extend the concept of conveyance to any remotely provided service.  Any cloud
service is considered network usage.

#### Internal
Internal usage occurs when artifacts are neither transferred external to organization nor used to
provide a service to customers.

### Typical Open Source Licenses
The [Open Source Initiative](https://opensource.org/licenses) evaluates and categorizes open source licenses.  A further classification
of OSI’s Licenses that are popular, widely used, or with strong communities from most restrictive to
least restrictive is: viral, dynamic linking, permissive.

#### Copyleft
A "copyleft" license requires the use of the same "copyleft" license by any derived work that is
"conveyed" to a customer. This class of viral licenses require source code disclosure of any derived
works. Dependency use of this class of license is may be damaging to Organization intellectual property.

#### Linking Exception
A "copyleft" license with an exception to allow proprietary software to link the artifact as
delivered into the product.  With this exception, dependent libraries (or jars) can be used without
triggering the viral license requirement.

#### Permissive
Permissive licenses allow the use of the licensed artifact for any purpose or use.  These license
usually disclaim any liability resulting from the use of that artifact.

### Reviewed Licenses
In the following table, reviewed licenses are marked as being acceptable (✓) or not acceptable (✗) 
for common uses based upon their virality.

| | Internal | Network | Linked | Conveyed |                     
| ---: | :---: | :---: | :---: | :---: |
| [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0) | ✓ | ✓ | ✓ | ✓ |
| [BSD "New" or "Revised" license](https://en.wikipedia.org/wiki/BSD_licenses#3-clause_license_\("BSD_License_2.0",_"Revised_BSD_License",_"New_BSD_License",_or_"Modified_BSD_License"\)) | ✓ | ✓ | ✓ | ✓ |
| ["FreeBSD" license](https://en.wikipedia.org/wiki/BSD_licenses#2-clause_license_\("Simplified_BSD_License"_or_"FreeBSD_License"\)) | ✓ | ✓ | ✓ | ✓ |
| [Common Development and Distribution License](https://en.wikipedia.org/wiki/Common_Development_and_Distribution_License) | ✓ | ✓ | ✓ | ✓ |
| [Eclipse Public License](https://www.eclipse.org/legal/epl-v10.html) | ✓ | ✓ | ✓ | ✓ |
| [GNU General Public License](https://www.gnu.org/licenses/gpl-3.0.en.html) | ✓ | ✓ | ✗ | ✗ |
| [GNU Affero General Public License](https://www.gnu.org/licenses/agpl-3.0.en.html) | ✓ | ✗ | ✗ | ✗ |
| ["Lesser" General Public License](https://www.gnu.org/licenses/lgpl-3.0.en.html) | ✓ | ✓ | ✓ | ✗ |
| [MIT license](https://en.wikipedia.org/wiki/MIT_License) | ✓ | ✓ | ✓ | ✓ |
| [Mozilla Public License 2.0](https://www.mozilla.org/en-US/MPL/2.0/) | ✓ | ✓ | ✓ | ✓ |
| [Oracle Binary Code License](http://www.oracle.com/technetwork/java/javase/terms/license/index.html) | ✓ | ✓ | ✓ | ✗ |
| No explicit license | ✗ | ✗ | ✗ | ✗ |

### Artifacts Without an Explicit License
Artifacts without an explicit licence or release grant is implicitly copyrighted material.  Artifacts without license cannot be used.

<p align="center">
  <a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png"/></a>
  <br />
  This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
</p>
