<Type Name="AuthenticationMethodFactory" FullName="Microsoft.Azure.Devices.Client.AuthenticationMethodFactory">
  <TypeSignature Language="C#" Value="public sealed class AuthenticationMethodFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit AuthenticationMethodFactory extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.AuthenticationMethodFactory" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class AuthenticationMethodFactory" />
  <TypeSignature Language="F#" Value="type AuthenticationMethodFactory = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a8c6f-101">実装のインスタンスを作成<see cref="T:Microsoft.Azure.Devices.Client.IAuthenticationMethod" />既知の認証パラメーターを基にします。</span><span class="sxs-lookup"><span data-stu-id="a8c6f-101">Creates an instance of an implementation of <see cref="T:Microsoft.Azure.Devices.Client.IAuthenticationMethod" /> based on known authentication parameters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthenticationMethodFactory ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.AuthenticationMethodFactory.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAuthenticationWithRegistrySymmetricKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.Client.IAuthenticationMethod CreateAuthenticationWithRegistrySymmetricKey (string deviceId, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.Client.IAuthenticationMethod CreateAuthenticationWithRegistrySymmetricKey(string deviceId, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.AuthenticationMethodFactory.CreateAuthenticationWithRegistrySymmetricKey(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAuthenticationWithRegistrySymmetricKey (deviceId As String, key As String) As IAuthenticationMethod" />
      <MemberSignature Language="F#" Value="static member CreateAuthenticationWithRegistrySymmetricKey : string * string -&gt; Microsoft.Azure.Devices.Client.IAuthenticationMethod" Usage="Microsoft.Azure.Devices.Client.AuthenticationMethodFactory.CreateAuthenticationWithRegistrySymmetricKey (deviceId, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.IAuthenticationMethod</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceId"><span data-ttu-id="a8c6f-102">デバイスの識別子です。</span><span class="sxs-lookup"><span data-stu-id="a8c6f-102">Device Identifier.</span></span></param>
        <param name="key"><span data-ttu-id="a8c6f-103">デバイス レジストリにデバイスに関連付けられたキー。</span><span class="sxs-lookup"><span data-stu-id="a8c6f-103">Key associated with the device in the device registry.</span></span></param>
        <summary>
            <span data-ttu-id="a8c6f-104">作成、<see cref="T:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithRegistrySymmetricKey" />インスタンス パラメーターに基づいています。</span><span class="sxs-lookup"><span data-stu-id="a8c6f-104">Creates a <see cref="T:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithRegistrySymmetricKey" /> instance based on the parameters.</span></span>
            </summary>
        <returns><span data-ttu-id="a8c6f-105"><see cref="T:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithRegistrySymmetricKey" /> クラスの新しいインスタンス。</span><span class="sxs-lookup"><span data-stu-id="a8c6f-105">A new instance of the <see cref="T:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithRegistrySymmetricKey" /> class.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAuthenticationWithSharedAccessPolicyKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.Client.IAuthenticationMethod CreateAuthenticationWithSharedAccessPolicyKey (string deviceId, string policyName, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.Client.IAuthenticationMethod CreateAuthenticationWithSharedAccessPolicyKey(string deviceId, string policyName, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.AuthenticationMethodFactory.CreateAuthenticationWithSharedAccessPolicyKey(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAuthenticationWithSharedAccessPolicyKey (deviceId As String, policyName As String, key As String) As IAuthenticationMethod" />
      <MemberSignature Language="F#" Value="static member CreateAuthenticationWithSharedAccessPolicyKey : string * string * string -&gt; Microsoft.Azure.Devices.Client.IAuthenticationMethod" Usage="Microsoft.Azure.Devices.Client.AuthenticationMethodFactory.CreateAuthenticationWithSharedAccessPolicyKey (deviceId, policyName, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.IAuthenticationMethod</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceId"><span data-ttu-id="a8c6f-106">デバイスの識別子です。</span><span class="sxs-lookup"><span data-stu-id="a8c6f-106">Device Identifier.</span></span></param>
        <param name="policyName"><span data-ttu-id="a8c6f-107">使用する共有アクセス ポリシーの名前です。</span><span class="sxs-lookup"><span data-stu-id="a8c6f-107">Name of the shared access policy to use.</span></span></param>
        <param name="key"><span data-ttu-id="a8c6f-108">共有アクセス ポリシーに関連付けられたキー。</span><span class="sxs-lookup"><span data-stu-id="a8c6f-108">Key associated with the shared access policy.</span></span></param>
        <summary>
            <span data-ttu-id="a8c6f-109">作成、<see cref="T:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithSharedAccessPolicyKey" />インスタンス パラメーターに基づいています。</span><span class="sxs-lookup"><span data-stu-id="a8c6f-109">Creates a <see cref="T:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithSharedAccessPolicyKey" /> instance based on the parameters.</span></span>
            </summary>
        <returns><span data-ttu-id="a8c6f-110"><see cref="T:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithSharedAccessPolicyKey" /> クラスの新しいインスタンス。</span><span class="sxs-lookup"><span data-stu-id="a8c6f-110">A new instance of the <see cref="T:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithSharedAccessPolicyKey" /> class.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAuthenticationWithToken">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.Client.IAuthenticationMethod CreateAuthenticationWithToken (string deviceId, string token);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.Client.IAuthenticationMethod CreateAuthenticationWithToken(string deviceId, string token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.AuthenticationMethodFactory.CreateAuthenticationWithToken(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAuthenticationWithToken (deviceId As String, token As String) As IAuthenticationMethod" />
      <MemberSignature Language="F#" Value="static member CreateAuthenticationWithToken : string * string -&gt; Microsoft.Azure.Devices.Client.IAuthenticationMethod" Usage="Microsoft.Azure.Devices.Client.AuthenticationMethodFactory.CreateAuthenticationWithToken (deviceId, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.IAuthenticationMethod</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="token" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceId"><span data-ttu-id="a8c6f-111">デバイスの識別子です。</span><span class="sxs-lookup"><span data-stu-id="a8c6f-111">Device Identifier.</span></span></param>
        <param name="token"><span data-ttu-id="a8c6f-112">デバイスに関連付けられているセキュリティ トークンです。</span><span class="sxs-lookup"><span data-stu-id="a8c6f-112">Security token associated with the device.</span></span></param>
        <summary>
            <span data-ttu-id="a8c6f-113">作成、<see cref="T:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithToken" />インスタンス パラメーターに基づいています。</span><span class="sxs-lookup"><span data-stu-id="a8c6f-113">Creates a <see cref="T:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithToken" /> instance based on the parameters.</span></span>
            </summary>
        <returns><span data-ttu-id="a8c6f-114"><see cref="T:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithToken" /> クラスの新しいインスタンス。</span><span class="sxs-lookup"><span data-stu-id="a8c6f-114">A new instance of the <see cref="T:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithToken" /> class.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>