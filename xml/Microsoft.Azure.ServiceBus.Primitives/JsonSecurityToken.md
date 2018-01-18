<Type Name="JsonSecurityToken" FullName="Microsoft.Azure.ServiceBus.Primitives.JsonSecurityToken">
  <TypeSignature Language="C#" Value="public class JsonSecurityToken : Microsoft.Azure.ServiceBus.Primitives.SecurityToken" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JsonSecurityToken extends Microsoft.Azure.ServiceBus.Primitives.SecurityToken" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.Primitives.JsonSecurityToken" />
  <TypeSignature Language="VB.NET" Value="Public Class JsonSecurityToken&#xA;Inherits SecurityToken" />
  <TypeSignature Language="F#" Value="type JsonSecurityToken = class&#xA;    inherit SecurityToken" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.ServiceBus.Primitives.SecurityToken</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="131dd-101">JWT 固有のプロパティの SecurityToken を拡張します。</span><span class="sxs-lookup"><span data-stu-id="131dd-101">Extends SecurityToken for JWT specific properties</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JsonSecurityToken (string rawToken, string audience);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string rawToken, string audience) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Primitives.JsonSecurityToken.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (rawToken As String, audience As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.Primitives.JsonSecurityToken : string * string -&gt; Microsoft.Azure.ServiceBus.Primitives.JsonSecurityToken" Usage="new Microsoft.Azure.ServiceBus.Primitives.JsonSecurityToken (rawToken, audience)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="rawToken" Type="System.String" />
        <Parameter Name="audience" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="rawToken"><span data-ttu-id="131dd-102">JSON Web Token 未加工の文字列</span><span class="sxs-lookup"><span data-stu-id="131dd-102">Raw JSON Web Token string</span></span></param>
        <param name="audience"><span data-ttu-id="131dd-103">対象ユーザー</span><span class="sxs-lookup"><span data-stu-id="131dd-103">The audience</span></span></param>
        <summary>
            <span data-ttu-id="131dd-104">
                      <see cref="T:Microsoft.Azure.ServiceBus.Primitives.JsonSecurityToken" /> クラスの新しいインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="131dd-104">Creates a new instance of the <see cref="T:Microsoft.Azure.ServiceBus.Primitives.JsonSecurityToken" /> class.</span></span>
</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>