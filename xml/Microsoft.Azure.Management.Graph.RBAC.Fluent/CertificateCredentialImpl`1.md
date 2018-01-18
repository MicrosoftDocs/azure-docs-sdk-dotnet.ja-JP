<Type Name="CertificateCredentialImpl&lt;T&gt;" FullName="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl&lt;T&gt;">
  <TypeSignature Language="C#" Value="public class CertificateCredentialImpl&lt;T&gt; : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IndexableRefreshableWrapper&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.ICertificateCredential,Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt;, Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IBlank&lt;T&gt;, Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IDefinition&lt;T&gt;, Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAttach&lt;T&gt;, Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAuthFile&lt;T&gt;, Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAuthFileCertificate&lt;T&gt;, Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAuthFileCertificatePassword&lt;T&gt;, Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithCertificateType&lt;T&gt;, Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithDuration&lt;T&gt;, Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithPublicKey&lt;T&gt;, Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithStartDate&lt;T&gt;, Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithSymmetricKey&lt;T&gt;, Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IBlank&lt;T&gt;, Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IUpdateDefinition&lt;T&gt;, Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAttach&lt;T&gt;, Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAuthFile&lt;T&gt;, Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAuthFileCertificate&lt;T&gt;, Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAuthFileCertificatePassword&lt;T&gt;, Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithCertificateType&lt;T&gt;, Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithDuration&lt;T&gt;, Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithPublicKey&lt;T&gt;, Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithStartDate&lt;T&gt;, Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithSymmetricKey&lt;T&gt;, Microsoft.Azure.Management.Graph.RBAC.Fluent.ICertificateCredential, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition&lt;T&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Update.IInUpdate&lt;T&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName where T : class" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateCredentialImpl`1&lt;class T&gt; extends Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IndexableRefreshableWrapper`2&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.ICertificateCredential, class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt; implements class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IBlank`1&lt;!T&gt;, class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IDefinition`1&lt;!T&gt;, class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAttach`1&lt;!T&gt;, class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAuthFile`1&lt;!T&gt;, class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAuthFileCertificate`1&lt;!T&gt;, class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAuthFileCertificatePassword`1&lt;!T&gt;, class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithCertificateType`1&lt;!T&gt;, class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithDuration`1&lt;!T&gt;, class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithPublicKey`1&lt;!T&gt;, class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithStartDate`1&lt;!T&gt;, class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithSymmetricKey`1&lt;!T&gt;, class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IBlank`1&lt;!T&gt;, class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IUpdateDefinition`1&lt;!T&gt;, class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAttach`1&lt;!T&gt;, class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAuthFile`1&lt;!T&gt;, class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAuthFileCertificate`1&lt;!T&gt;, class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAuthFileCertificatePassword`1&lt;!T&gt;, class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithCertificateType`1&lt;!T&gt;, class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithDuration`1&lt;!T&gt;, class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithPublicKey`1&lt;!T&gt;, class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithStartDate`1&lt;!T&gt;, class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithSymmetricKey`1&lt;!T&gt;, class Microsoft.Azure.Management.Graph.RBAC.Fluent.ICertificateCredential, class Microsoft.Azure.Management.Graph.RBAC.Fluent.ICredential, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition`1&lt;!T&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Update.IInUpdate`1&lt;!T&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateCredentialImpl(Of T)&#xA;Inherits IndexableRefreshableWrapper(Of ICertificateCredential, KeyCredential)&#xA;Implements IBeta, IBlank(Of T), IBlank(Of T), ICertificateCredential, IDefinition(Of T), IHasId, IHasInner(Of KeyCredential), IHasName, IInDefinition(Of T), IInUpdate(Of T), IUpdateDefinition(Of T), IWithAttach(Of T), IWithAttach(Of T), IWithAuthFile(Of T), IWithAuthFile(Of T), IWithAuthFileCertificate(Of T), IWithAuthFileCertificate(Of T), IWithAuthFileCertificatePassword(Of T), IWithAuthFileCertificatePassword(Of T), IWithCertificateType(Of T), IWithCertificateType(Of T), IWithDuration(Of T), IWithDuration(Of T), IWithPublicKey(Of T), IWithPublicKey(Of T), IWithStartDate(Of T), IWithStartDate(Of T), IWithSymmetricKey(Of T), IWithSymmetricKey(Of T)" />
  <TypeSignature Language="F#" Value="type CertificateCredentialImpl&lt;'T (requires 'T : null)&gt; = class&#xA;    inherit IndexableRefreshableWrapper&lt;ICertificateCredential, KeyCredential&gt;&#xA;    interface ICertificateCredential&#xA;    interface IBeta&#xA;    interface ICredential&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasInner&lt;KeyCredential&gt;&#xA;    interface IDefinition&lt;'T (requires 'T : null)&gt;&#xA;    interface IBlank&lt;'T (requires 'T : null)&gt;&#xA;    interface IWithCertificateType&lt;'T (requires 'T : null)&gt;&#xA;    interface IWithPublicKey&lt;'T (requires 'T : null)&gt;&#xA;    interface IWithSymmetricKey&lt;'T (requires 'T : null)&gt;&#xA;    interface IWithAttach&lt;'T (requires 'T : null)&gt;&#xA;    interface IInDefinition&lt;'T (requires 'T : null)&gt;&#xA;    interface IWithStartDate&lt;'T (requires 'T : null)&gt;&#xA;    interface IWithDuration&lt;'T (requires 'T : null)&gt;&#xA;    interface IWithAuthFile&lt;'T (requires 'T : null)&gt;&#xA;    interface IWithAuthFileCertificate&lt;'T (requires 'T : null)&gt;&#xA;    interface IWithAuthFileCertificatePassword&lt;'T (requires 'T : null)&gt;&#xA;    interface IUpdateDefinition&lt;'T (requires 'T : null)&gt;&#xA;    interface IBlank&lt;'T (requires 'T : null)&gt;&#xA;    interface IWithCertificateType&lt;'T (requires 'T : null)&gt;&#xA;    interface IWithPublicKey&lt;'T (requires 'T : null)&gt;&#xA;    interface IWithSymmetricKey&lt;'T (requires 'T : null)&gt;&#xA;    interface IWithAttach&lt;'T (requires 'T : null)&gt;&#xA;    interface IInUpdate&lt;'T (requires 'T : null)&gt;&#xA;    interface IWithStartDate&lt;'T (requires 'T : null)&gt;&#xA;    interface IWithDuration&lt;'T (requires 'T : null)&gt;&#xA;    interface IWithAuthFile&lt;'T (requires 'T : null)&gt;&#xA;    interface IWithAuthFileCertificate&lt;'T (requires 'T : null)&gt;&#xA;    interface IWithAuthFileCertificatePassword&lt;'T (requires 'T : null)&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IndexableRefreshableWrapper&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.ICertificateCredential,Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Management.Graph.RBAC.Fluent.ICertificateCredential</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="!1">Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IBlank&lt;T&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IDefinition&lt;T&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAttach&lt;T&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAuthFile&lt;T&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAuthFileCertificate&lt;T&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAuthFileCertificatePassword&lt;T&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithCertificateType&lt;T&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithDuration&lt;T&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithPublicKey&lt;T&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithStartDate&lt;T&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithSymmetricKey&lt;T&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IBlank&lt;T&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IUpdateDefinition&lt;T&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAttach&lt;T&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAuthFile&lt;T&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAuthFileCertificate&lt;T&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAuthFileCertificatePassword&lt;T&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithCertificateType&lt;T&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithDuration&lt;T&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithPublicKey&lt;T&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithStartDate&lt;T&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithSymmetricKey&lt;T&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Graph.RBAC.Fluent.ICertificateCredential</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition&lt;T&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Update.IInUpdate&lt;T&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T">To be added.</typeparam>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Attach">
      <MemberSignature Language="C#" Value="public T Attach ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance !T Attach() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.Attach" />
      <MemberSignature Language="VB.NET" Value="Public Function Attach () As T" />
      <MemberSignature Language="F#" Value="member this.Attach : unit -&gt; 'T" Usage="certificateCredentialImpl.Attach " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition`1.Attach</InterfaceMember>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Update.IInUpdate`1.Attach</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDate">
      <MemberSignature Language="C#" Value="public DateTime EndDate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance valuetype System.DateTime EndDate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.EndDate" />
      <MemberSignature Language="VB.NET" Value="Public Function EndDate () As DateTime" />
      <MemberSignature Language="F#" Value="member this.EndDate : unit -&gt; DateTime" Usage="certificateCredentialImpl.EndDate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetInnerAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt; GetInnerAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt; GetInnerAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.GetInnerAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.GetInnerAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt;" Usage="certificateCredentialImpl.GetInnerAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1/&lt;GetInnerAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string Id() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.Id" />
      <MemberSignature Language="VB.NET" Value="Public Function Id () As String" />
      <MemberSignature Language="F#" Value="member this.Id : unit -&gt; string" Usage="certificateCredentialImpl.Id " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAuthFile&lt;T&gt;.WithAuthFileToExport">
      <MemberSignature Language="C#" Value="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAuthFileCertificate&lt;T&gt; IWithAuthFile&lt;T&gt;.WithAuthFileToExport (System.IO.StreamWriter outputStream);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAuthFileCertificate`1&lt;!T&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAuthFile&lt;T&gt;.WithAuthFileToExport(class System.IO.StreamWriter outputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.Microsoft#Azure#Management#Graph#RBAC#Fluent#CertificateCredential#Definition#IWithAuthFile&lt;T&gt;#WithAuthFileToExport(System.IO.StreamWriter)" />
      <MemberSignature Language="VB.NET" Value="Function WithAuthFileToExport (outputStream As StreamWriter) As IWithAuthFileCertificate(Of T) Implements IWithAuthFile(Of T).WithAuthFileToExport" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAuthFile`1.WithAuthFileToExport(System.IO.StreamWriter)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAuthFileCertificate&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="outputStream" Type="System.IO.StreamWriter" />
      </Parameters>
      <Docs>
        <param name="outputStream">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAuthFileCertificate&lt;T&gt;.WithPrivateKeyFile">
      <MemberSignature Language="C#" Value="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAuthFileCertificatePassword&lt;T&gt; IWithAuthFileCertificate&lt;T&gt;.WithPrivateKeyFile (string privateKeyPath);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAuthFileCertificatePassword`1&lt;!T&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAuthFileCertificate&lt;T&gt;.WithPrivateKeyFile(string privateKeyPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.Microsoft#Azure#Management#Graph#RBAC#Fluent#CertificateCredential#Definition#IWithAuthFileCertificate&lt;T&gt;#WithPrivateKeyFile(System.String)" />
      <MemberSignature Language="VB.NET" Value="Function WithPrivateKeyFile (privateKeyPath As String) As IWithAuthFileCertificatePassword(Of T) Implements IWithAuthFileCertificate(Of T).WithPrivateKeyFile" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAuthFileCertificate`1.WithPrivateKeyFile(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAuthFileCertificatePassword&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="privateKeyPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="privateKeyPath">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAuthFileCertificatePassword&lt;T&gt;.WithPrivateKeyPassword">
      <MemberSignature Language="C#" Value="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAttach&lt;T&gt; IWithAuthFileCertificatePassword&lt;T&gt;.WithPrivateKeyPassword (string privateKeyPassword);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAttach`1&lt;!T&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAuthFileCertificatePassword&lt;T&gt;.WithPrivateKeyPassword(string privateKeyPassword) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.Microsoft#Azure#Management#Graph#RBAC#Fluent#CertificateCredential#Definition#IWithAuthFileCertificatePassword&lt;T&gt;#WithPrivateKeyPassword(System.String)" />
      <MemberSignature Language="VB.NET" Value="Function WithPrivateKeyPassword (privateKeyPassword As String) As IWithAttach(Of T) Implements IWithAuthFileCertificatePassword(Of T).WithPrivateKeyPassword" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAuthFileCertificatePassword`1.WithPrivateKeyPassword(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAttach&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="privateKeyPassword" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="privateKeyPassword">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithCertificateType&lt;T&gt;.WithAsymmetricX509Certificate">
      <MemberSignature Language="C#" Value="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithPublicKey&lt;T&gt; IWithCertificateType&lt;T&gt;.WithAsymmetricX509Certificate ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithPublicKey`1&lt;!T&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithCertificateType&lt;T&gt;.WithAsymmetricX509Certificate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.Microsoft#Azure#Management#Graph#RBAC#Fluent#CertificateCredential#Definition#IWithCertificateType&lt;T&gt;#WithAsymmetricX509Certificate" />
      <MemberSignature Language="VB.NET" Value="Function WithAsymmetricX509Certificate () As IWithPublicKey(Of T) Implements IWithCertificateType(Of T).WithAsymmetricX509Certificate" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithCertificateType`1.WithAsymmetricX509Certificate</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithPublicKey&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithCertificateType&lt;T&gt;.WithSymmetricEncryption">
      <MemberSignature Language="C#" Value="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithSymmetricKey&lt;T&gt; IWithCertificateType&lt;T&gt;.WithSymmetricEncryption ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithSymmetricKey`1&lt;!T&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithCertificateType&lt;T&gt;.WithSymmetricEncryption() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.Microsoft#Azure#Management#Graph#RBAC#Fluent#CertificateCredential#Definition#IWithCertificateType&lt;T&gt;#WithSymmetricEncryption" />
      <MemberSignature Language="VB.NET" Value="Function WithSymmetricEncryption () As IWithSymmetricKey(Of T) Implements IWithCertificateType(Of T).WithSymmetricEncryption" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithCertificateType`1.WithSymmetricEncryption</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithSymmetricKey&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithDuration&lt;T&gt;.WithDuration">
      <MemberSignature Language="C#" Value="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAttach&lt;T&gt; IWithDuration&lt;T&gt;.WithDuration (TimeSpan duration);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAttach`1&lt;!T&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithDuration&lt;T&gt;.WithDuration(valuetype System.TimeSpan duration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.Microsoft#Azure#Management#Graph#RBAC#Fluent#CertificateCredential#Definition#IWithDuration&lt;T&gt;#WithDuration(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Function WithDuration (duration As TimeSpan) As IWithAttach(Of T) Implements IWithDuration(Of T).WithDuration" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithDuration`1.WithDuration(System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAttach&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="duration" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="duration">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithPublicKey&lt;T&gt;.WithPublicKey">
      <MemberSignature Language="C#" Value="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAttach&lt;T&gt; IWithPublicKey&lt;T&gt;.WithPublicKey (byte[] certificate);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAttach`1&lt;!T&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithPublicKey&lt;T&gt;.WithPublicKey(unsigned int8[] certificate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.Microsoft#Azure#Management#Graph#RBAC#Fluent#CertificateCredential#Definition#IWithPublicKey&lt;T&gt;#WithPublicKey(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Function WithPublicKey (certificate As Byte()) As IWithAttach(Of T) Implements IWithPublicKey(Of T).WithPublicKey" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithPublicKey`1.WithPublicKey(System.Byte[])</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAttach&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="certificate" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="certificate">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithStartDate&lt;T&gt;.WithStartDate">
      <MemberSignature Language="C#" Value="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAttach&lt;T&gt; IWithStartDate&lt;T&gt;.WithStartDate (DateTime startDate);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAttach`1&lt;!T&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithStartDate&lt;T&gt;.WithStartDate(valuetype System.DateTime startDate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.Microsoft#Azure#Management#Graph#RBAC#Fluent#CertificateCredential#Definition#IWithStartDate&lt;T&gt;#WithStartDate(System.DateTime)" />
      <MemberSignature Language="VB.NET" Value="Function WithStartDate (startDate As DateTime) As IWithAttach(Of T) Implements IWithStartDate(Of T).WithStartDate" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithStartDate`1.WithStartDate(System.DateTime)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAttach&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="startDate" Type="System.DateTime" />
      </Parameters>
      <Docs>
        <param name="startDate">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithSymmetricKey&lt;T&gt;.WithSecretKey">
      <MemberSignature Language="C#" Value="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAttach&lt;T&gt; IWithSymmetricKey&lt;T&gt;.WithSecretKey (byte[] secret);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAttach`1&lt;!T&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithSymmetricKey&lt;T&gt;.WithSecretKey(unsigned int8[] secret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.Microsoft#Azure#Management#Graph#RBAC#Fluent#CertificateCredential#Definition#IWithSymmetricKey&lt;T&gt;#WithSecretKey(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Function WithSecretKey (secret As Byte()) As IWithAttach(Of T) Implements IWithSymmetricKey(Of T).WithSecretKey" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithSymmetricKey`1.WithSecretKey(System.Byte[])</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.Definition.IWithAttach&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="secret" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="secret">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAuthFile&lt;T&gt;.WithAuthFileToExport">
      <MemberSignature Language="C#" Value="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAuthFileCertificate&lt;T&gt; IWithAuthFile&lt;T&gt;.WithAuthFileToExport (System.IO.StreamWriter outputStream);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAuthFileCertificate`1&lt;!T&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAuthFile&lt;T&gt;.WithAuthFileToExport(class System.IO.StreamWriter outputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.Microsoft#Azure#Management#Graph#RBAC#Fluent#CertificateCredential#UpdateDefinition#IWithAuthFile&lt;T&gt;#WithAuthFileToExport(System.IO.StreamWriter)" />
      <MemberSignature Language="VB.NET" Value="Function WithAuthFileToExport (outputStream As StreamWriter) As IWithAuthFileCertificate(Of T) Implements IWithAuthFile(Of T).WithAuthFileToExport" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAuthFile`1.WithAuthFileToExport(System.IO.StreamWriter)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAuthFileCertificate&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="outputStream" Type="System.IO.StreamWriter" />
      </Parameters>
      <Docs>
        <param name="outputStream">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAuthFileCertificate&lt;T&gt;.WithPrivateKeyFile">
      <MemberSignature Language="C#" Value="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAuthFileCertificatePassword&lt;T&gt; IWithAuthFileCertificate&lt;T&gt;.WithPrivateKeyFile (string privateKeyPath);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAuthFileCertificatePassword`1&lt;!T&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAuthFileCertificate&lt;T&gt;.WithPrivateKeyFile(string privateKeyPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.Microsoft#Azure#Management#Graph#RBAC#Fluent#CertificateCredential#UpdateDefinition#IWithAuthFileCertificate&lt;T&gt;#WithPrivateKeyFile(System.String)" />
      <MemberSignature Language="VB.NET" Value="Function WithPrivateKeyFile (privateKeyPath As String) As IWithAuthFileCertificatePassword(Of T) Implements IWithAuthFileCertificate(Of T).WithPrivateKeyFile" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAuthFileCertificate`1.WithPrivateKeyFile(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAuthFileCertificatePassword&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="privateKeyPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="privateKeyPath">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAuthFileCertificatePassword&lt;T&gt;.WithPrivateKeyPassword">
      <MemberSignature Language="C#" Value="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAttach&lt;T&gt; IWithAuthFileCertificatePassword&lt;T&gt;.WithPrivateKeyPassword (string privateKeyPassword);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAttach`1&lt;!T&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAuthFileCertificatePassword&lt;T&gt;.WithPrivateKeyPassword(string privateKeyPassword) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.Microsoft#Azure#Management#Graph#RBAC#Fluent#CertificateCredential#UpdateDefinition#IWithAuthFileCertificatePassword&lt;T&gt;#WithPrivateKeyPassword(System.String)" />
      <MemberSignature Language="VB.NET" Value="Function WithPrivateKeyPassword (privateKeyPassword As String) As IWithAttach(Of T) Implements IWithAuthFileCertificatePassword(Of T).WithPrivateKeyPassword" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAuthFileCertificatePassword`1.WithPrivateKeyPassword(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAttach&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="privateKeyPassword" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="privateKeyPassword">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithCertificateType&lt;T&gt;.WithAsymmetricX509Certificate">
      <MemberSignature Language="C#" Value="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithPublicKey&lt;T&gt; IWithCertificateType&lt;T&gt;.WithAsymmetricX509Certificate ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithPublicKey`1&lt;!T&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithCertificateType&lt;T&gt;.WithAsymmetricX509Certificate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.Microsoft#Azure#Management#Graph#RBAC#Fluent#CertificateCredential#UpdateDefinition#IWithCertificateType&lt;T&gt;#WithAsymmetricX509Certificate" />
      <MemberSignature Language="VB.NET" Value="Function WithAsymmetricX509Certificate () As IWithPublicKey(Of T) Implements IWithCertificateType(Of T).WithAsymmetricX509Certificate" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithCertificateType`1.WithAsymmetricX509Certificate</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithPublicKey&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithCertificateType&lt;T&gt;.WithSymmetricEncryption">
      <MemberSignature Language="C#" Value="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithSymmetricKey&lt;T&gt; IWithCertificateType&lt;T&gt;.WithSymmetricEncryption ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithSymmetricKey`1&lt;!T&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithCertificateType&lt;T&gt;.WithSymmetricEncryption() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.Microsoft#Azure#Management#Graph#RBAC#Fluent#CertificateCredential#UpdateDefinition#IWithCertificateType&lt;T&gt;#WithSymmetricEncryption" />
      <MemberSignature Language="VB.NET" Value="Function WithSymmetricEncryption () As IWithSymmetricKey(Of T) Implements IWithCertificateType(Of T).WithSymmetricEncryption" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithCertificateType`1.WithSymmetricEncryption</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithSymmetricKey&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithDuration&lt;T&gt;.WithDuration">
      <MemberSignature Language="C#" Value="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAttach&lt;T&gt; IWithDuration&lt;T&gt;.WithDuration (TimeSpan duration);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAttach`1&lt;!T&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithDuration&lt;T&gt;.WithDuration(valuetype System.TimeSpan duration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.Microsoft#Azure#Management#Graph#RBAC#Fluent#CertificateCredential#UpdateDefinition#IWithDuration&lt;T&gt;#WithDuration(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Function WithDuration (duration As TimeSpan) As IWithAttach(Of T) Implements IWithDuration(Of T).WithDuration" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithDuration`1.WithDuration(System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAttach&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="duration" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="duration">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithPublicKey&lt;T&gt;.WithPublicKey">
      <MemberSignature Language="C#" Value="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAttach&lt;T&gt; IWithPublicKey&lt;T&gt;.WithPublicKey (byte[] certificate);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAttach`1&lt;!T&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithPublicKey&lt;T&gt;.WithPublicKey(unsigned int8[] certificate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.Microsoft#Azure#Management#Graph#RBAC#Fluent#CertificateCredential#UpdateDefinition#IWithPublicKey&lt;T&gt;#WithPublicKey(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Function WithPublicKey (certificate As Byte()) As IWithAttach(Of T) Implements IWithPublicKey(Of T).WithPublicKey" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithPublicKey`1.WithPublicKey(System.Byte[])</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAttach&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="certificate" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="certificate">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithStartDate&lt;T&gt;.WithStartDate">
      <MemberSignature Language="C#" Value="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAttach&lt;T&gt; IWithStartDate&lt;T&gt;.WithStartDate (DateTime startDate);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAttach`1&lt;!T&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithStartDate&lt;T&gt;.WithStartDate(valuetype System.DateTime startDate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.Microsoft#Azure#Management#Graph#RBAC#Fluent#CertificateCredential#UpdateDefinition#IWithStartDate&lt;T&gt;#WithStartDate(System.DateTime)" />
      <MemberSignature Language="VB.NET" Value="Function WithStartDate (startDate As DateTime) As IWithAttach(Of T) Implements IWithStartDate(Of T).WithStartDate" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithStartDate`1.WithStartDate(System.DateTime)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAttach&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="startDate" Type="System.DateTime" />
      </Parameters>
      <Docs>
        <param name="startDate">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithSymmetricKey&lt;T&gt;.WithSecretKey">
      <MemberSignature Language="C#" Value="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAttach&lt;T&gt; IWithSymmetricKey&lt;T&gt;.WithSecretKey (byte[] secret);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAttach`1&lt;!T&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithSymmetricKey&lt;T&gt;.WithSecretKey(unsigned int8[] secret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.Microsoft#Azure#Management#Graph#RBAC#Fluent#CertificateCredential#UpdateDefinition#IWithSymmetricKey&lt;T&gt;#WithSecretKey(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Function WithSecretKey (secret As Byte()) As IWithAttach(Of T) Implements IWithSymmetricKey(Of T).WithSecretKey" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithSymmetricKey`1.WithSecretKey(System.Byte[])</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredential.UpdateDefinition.IWithAttach&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="secret" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="secret">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.Graph.RBAC.Fluent.ICredential.EndDate">
      <MemberSignature Language="C#" Value="DateTime Microsoft.Azure.Management.Graph.RBAC.Fluent.ICredential.EndDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime Microsoft.Azure.Management.Graph.RBAC.Fluent.ICredential.EndDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.Microsoft#Azure#Management#Graph#RBAC#Fluent#ICredential#EndDate" />
      <MemberSignature Language="VB.NET" Value=" ReadOnly Property EndDate As DateTime Implements ICredential.EndDate" />
      <MemberSignature Language="F#" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl&lt;'T (requires 'T : null)&gt;.Microsoft.Azure.Management.Graph.RBAC.Fluent.ICredential.EndDate" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Graph.RBAC.Fluent.ICredential.EndDate</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.Graph.RBAC.Fluent.ICredential.StartDate">
      <MemberSignature Language="C#" Value="DateTime Microsoft.Azure.Management.Graph.RBAC.Fluent.ICredential.StartDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime Microsoft.Azure.Management.Graph.RBAC.Fluent.ICredential.StartDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.Microsoft#Azure#Management#Graph#RBAC#Fluent#ICredential#StartDate" />
      <MemberSignature Language="VB.NET" Value=" ReadOnly Property StartDate As DateTime Implements ICredential.StartDate" />
      <MemberSignature Language="F#" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl&lt;'T (requires 'T : null)&gt;.Microsoft.Azure.Management.Graph.RBAC.Fluent.ICredential.StartDate" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Graph.RBAC.Fluent.ICredential.StartDate</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.Graph.RBAC.Fluent.ICredential.Value">
      <MemberSignature Language="C#" Value="string Microsoft.Azure.Management.Graph.RBAC.Fluent.ICredential.Value { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Microsoft.Azure.Management.Graph.RBAC.Fluent.ICredential.Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.Microsoft#Azure#Management#Graph#RBAC#Fluent#ICredential#Value" />
      <MemberSignature Language="VB.NET" Value=" ReadOnly Property Value As String Implements ICredential.Value" />
      <MemberSignature Language="F#" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl&lt;'T (requires 'T : null)&gt;.Microsoft.Azure.Management.Graph.RBAC.Fluent.ICredential.Value" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Graph.RBAC.Fluent.ICredential.Value</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition&lt;T&gt;.Attach">
      <MemberSignature Language="C#" Value="T IInDefinition&lt;T&gt;.Attach ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance !T Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition&lt;T&gt;.Attach() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.Microsoft#Azure#Management#ResourceManager#Fluent#Core#ChildResource#Definition#IInDefinition&lt;T&gt;#Attach" />
      <MemberSignature Language="VB.NET" Value="Function Attach () As T Implements IInDefinition(Of T).Attach" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition`1.Attach</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Update.IInUpdate&lt;T&gt;.Attach">
      <MemberSignature Language="C#" Value="T IInUpdate&lt;T&gt;.Attach ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance !T Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Update.IInUpdate&lt;T&gt;.Attach() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.Microsoft#Azure#Management#ResourceManager#Fluent#Core#ChildResource#Update#IInUpdate&lt;T&gt;#Attach" />
      <MemberSignature Language="VB.NET" Value="Function Attach () As T Implements IInUpdate(Of T).Attach" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Update.IInUpdate`1.Attach</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId.Id">
      <MemberSignature Language="C#" Value="string Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId.Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId.Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.Microsoft#Azure#Management#ResourceManager#Fluent#Core#IHasId#Id" />
      <MemberSignature Language="VB.NET" Value=" ReadOnly Property Id As String Implements IHasId.Id" />
      <MemberSignature Language="F#" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl&lt;'T (requires 'T : null)&gt;.Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId.Id" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId.Id</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName.Name">
      <MemberSignature Language="C#" Value="string Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName.Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName.Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.Microsoft#Azure#Management#ResourceManager#Fluent#Core#IHasName#Name" />
      <MemberSignature Language="VB.NET" Value=" ReadOnly Property Name As String Implements IHasName.Name" />
      <MemberSignature Language="F#" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl&lt;'T (requires 'T : null)&gt;.Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName.Name" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName.Name</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string Name() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.Name" />
      <MemberSignature Language="VB.NET" Value="Public Function Name () As String" />
      <MemberSignature Language="F#" Value="member this.Name : unit -&gt; string" Usage="certificateCredentialImpl.Name " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.ICertificateCredential&gt; RefreshAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.ICertificateCredential&gt; RefreshAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.RefreshAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.RefreshAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.ICertificateCredential&gt;" Usage="certificateCredentialImpl.RefreshAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1/&lt;RefreshAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.ICertificateCredential&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartDate">
      <MemberSignature Language="C#" Value="public DateTime StartDate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance valuetype System.DateTime StartDate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.StartDate" />
      <MemberSignature Language="VB.NET" Value="Public Function StartDate () As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartDate : unit -&gt; DateTime" Usage="certificateCredentialImpl.StartDate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public string Value ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string Value() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.Value" />
      <MemberSignature Language="VB.NET" Value="Public Function Value () As String" />
      <MemberSignature Language="F#" Value="member this.Value : unit -&gt; string" Usage="certificateCredentialImpl.Value " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithAsymmetricX509Certificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl&lt;T&gt; WithAsymmetricX509Certificate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1&lt;!T&gt; WithAsymmetricX509Certificate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.WithAsymmetricX509Certificate" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAsymmetricX509Certificate () As CertificateCredentialImpl(Of T)" />
      <MemberSignature Language="F#" Value="member this.WithAsymmetricX509Certificate : unit -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl&lt;'T (requires 'T : null)&gt;" Usage="certificateCredentialImpl.WithAsymmetricX509Certificate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithAuthFileToExport">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl&lt;T&gt; WithAuthFileToExport (System.IO.StreamWriter outputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1&lt;!T&gt; WithAuthFileToExport(class System.IO.StreamWriter outputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.WithAuthFileToExport(System.IO.StreamWriter)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAuthFileToExport (outputStream As StreamWriter) As CertificateCredentialImpl(Of T)" />
      <MemberSignature Language="F#" Value="member this.WithAuthFileToExport : System.IO.StreamWriter -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl&lt;'T (requires 'T : null)&gt;" Usage="certificateCredentialImpl.WithAuthFileToExport outputStream" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="outputStream" Type="System.IO.StreamWriter" />
      </Parameters>
      <Docs>
        <param name="outputStream">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithDuration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl&lt;T&gt; WithDuration (TimeSpan duration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1&lt;!T&gt; WithDuration(valuetype System.TimeSpan duration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.WithDuration(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDuration (duration As TimeSpan) As CertificateCredentialImpl(Of T)" />
      <MemberSignature Language="F#" Value="member this.WithDuration : TimeSpan -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl&lt;'T (requires 'T : null)&gt;" Usage="certificateCredentialImpl.WithDuration duration" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="duration" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="duration">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithPrivateKeyFile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl&lt;T&gt; WithPrivateKeyFile (string privateKeyPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1&lt;!T&gt; WithPrivateKeyFile(string privateKeyPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.WithPrivateKeyFile(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrivateKeyFile (privateKeyPath As String) As CertificateCredentialImpl(Of T)" />
      <MemberSignature Language="F#" Value="member this.WithPrivateKeyFile : string -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl&lt;'T (requires 'T : null)&gt;" Usage="certificateCredentialImpl.WithPrivateKeyFile privateKeyPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="privateKeyPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="privateKeyPath">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithPrivateKeyPassword">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl&lt;T&gt; WithPrivateKeyPassword (string privateKeyPassword);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1&lt;!T&gt; WithPrivateKeyPassword(string privateKeyPassword) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.WithPrivateKeyPassword(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrivateKeyPassword (privateKeyPassword As String) As CertificateCredentialImpl(Of T)" />
      <MemberSignature Language="F#" Value="member this.WithPrivateKeyPassword : string -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl&lt;'T (requires 'T : null)&gt;" Usage="certificateCredentialImpl.WithPrivateKeyPassword privateKeyPassword" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="privateKeyPassword" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="privateKeyPassword">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithPublicKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl&lt;T&gt; WithPublicKey (byte[] certificate);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1&lt;!T&gt; WithPublicKey(unsigned int8[] certificate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.WithPublicKey(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPublicKey (certificate As Byte()) As CertificateCredentialImpl(Of T)" />
      <MemberSignature Language="F#" Value="member this.WithPublicKey : byte[] -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl&lt;'T (requires 'T : null)&gt;" Usage="certificateCredentialImpl.WithPublicKey certificate" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="certificate" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="certificate">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithSecretKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl&lt;T&gt; WithSecretKey (byte[] secret);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1&lt;!T&gt; WithSecretKey(unsigned int8[] secret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.WithSecretKey(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSecretKey (secret As Byte()) As CertificateCredentialImpl(Of T)" />
      <MemberSignature Language="F#" Value="member this.WithSecretKey : byte[] -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl&lt;'T (requires 'T : null)&gt;" Usage="certificateCredentialImpl.WithSecretKey secret" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="secret" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="secret">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithStartDate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl&lt;T&gt; WithStartDate (DateTime startDate);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1&lt;!T&gt; WithStartDate(valuetype System.DateTime startDate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.WithStartDate(System.DateTime)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStartDate (startDate As DateTime) As CertificateCredentialImpl(Of T)" />
      <MemberSignature Language="F#" Value="member this.WithStartDate : DateTime -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl&lt;'T (requires 'T : null)&gt;" Usage="certificateCredentialImpl.WithStartDate startDate" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="startDate" Type="System.DateTime" />
      </Parameters>
      <Docs>
        <param name="startDate">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithSymmetricEncryption">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl&lt;T&gt; WithSymmetricEncryption ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1&lt;!T&gt; WithSymmetricEncryption() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl`1.WithSymmetricEncryption" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSymmetricEncryption () As CertificateCredentialImpl(Of T)" />
      <MemberSignature Language="F#" Value="member this.WithSymmetricEncryption : unit -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl&lt;'T (requires 'T : null)&gt;" Usage="certificateCredentialImpl.WithSymmetricEncryption " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.CertificateCredentialImpl&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>