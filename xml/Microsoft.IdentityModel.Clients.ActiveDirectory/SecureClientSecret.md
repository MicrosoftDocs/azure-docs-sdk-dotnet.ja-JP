<Type Name="SecureClientSecret" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.SecureClientSecret">
  <TypeSignature Language="C#" Value="public class SecureClientSecret : Microsoft.IdentityModel.Clients.ActiveDirectory.ISecureClientSecret" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SecureClientSecret extends System.Object implements class Microsoft.IdentityModel.Clients.ActiveDirectory.ISecureClientSecret" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.SecureClientSecret" />
  <TypeSignature Language="VB.NET" Value="Public Class SecureClientSecret&#xA;Implements ISecureClientSecret" />
  <TypeSignature Language="F#" Value="type SecureClientSecret = class&#xA;    interface ISecureClientSecret" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
    <AssemblyVersion>3.16.0.14</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
    <AssemblyVersion>3.17.3.35304</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.IdentityModel.Clients.ActiveDirectory.ISecureClientSecret</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="633a8-101">このクラスは、クライアント シークレットを SecureString として API に渡すできます。</span><span class="sxs-lookup"><span data-stu-id="633a8-101">This class allows to pass client secret as a SecureString to the API.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecureClientSecret (System.Security.SecureString secret);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Security.SecureString secret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.SecureClientSecret.#ctor(System.Security.SecureString)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (secret As SecureString)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.SecureClientSecret : System.Security.SecureString -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.SecureClientSecret" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.SecureClientSecret secret" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="secret" Type="System.Security.SecureString" />
      </Parameters>
      <Docs>
        <param name="secret"><span data-ttu-id="633a8-102">SecureString シークレット。</span><span class="sxs-lookup"><span data-stu-id="633a8-102">SecureString secret.</span></span> <span data-ttu-id="633a8-103">必須であり、null にすることはできません。</span><span class="sxs-lookup"><span data-stu-id="633a8-103">Required and cannot be null.</span></span></param>
        <summary>
            <span data-ttu-id="633a8-104">必要なコンス トラクター</span><span class="sxs-lookup"><span data-stu-id="633a8-104">Required Constructor</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplyTo">
      <MemberSignature Language="C#" Value="public void ApplyTo (System.Collections.Generic.IDictionary&lt;string,string&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ApplyTo(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.SecureClientSecret.ApplyTo(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub ApplyTo (parameters As IDictionary(Of String, String))" />
      <MemberSignature Language="F#" Value="abstract member ApplyTo : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; unit&#xA;override this.ApplyTo : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; unit" Usage="secureClientSecret.ApplyTo parameters" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.IdentityModel.Clients.ActiveDirectory.ISecureClientSecret.ApplyTo(System.Collections.Generic.IDictionary{System.String,System.String})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="parameters"><span data-ttu-id="633a8-105">サーバーに送信される、securestring が適用される辞書</span><span class="sxs-lookup"><span data-stu-id="633a8-105">Dictionary to which the securestring is applied to be sent to server</span></span></param>
        <summary>
            <span data-ttu-id="633a8-106">ディクショナリに、シークレットを適用します。</span><span class="sxs-lookup"><span data-stu-id="633a8-106">Applies the secret to the dictionary.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>