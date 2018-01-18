<Type Name="ServiceAuthenticationWithSharedAccessPolicyToken" FullName="Microsoft.Azure.Devices.ServiceAuthenticationWithSharedAccessPolicyToken">
  <TypeSignature Language="C#" Value="public sealed class ServiceAuthenticationWithSharedAccessPolicyToken : Microsoft.Azure.Devices.IAuthenticationMethod" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceAuthenticationWithSharedAccessPolicyToken extends System.Object implements class Microsoft.Azure.Devices.IAuthenticationMethod" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.ServiceAuthenticationWithSharedAccessPolicyToken" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceAuthenticationWithSharedAccessPolicyToken&#xA;Implements IAuthenticationMethod" />
  <TypeSignature Language="F#" Value="type ServiceAuthenticationWithSharedAccessPolicyToken = class&#xA;    interface IAuthenticationMethod" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Devices.IAuthenticationMethod</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="336fd-101">共有アクセス ポリシーのトークンを使用する認証方法です。</span><span class="sxs-lookup"><span data-stu-id="336fd-101">Authentication method that uses a shared access policy token.</span></span> 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceAuthenticationWithSharedAccessPolicyToken (string policyName, string token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string policyName, string token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ServiceAuthenticationWithSharedAccessPolicyToken.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (policyName As String, token As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.ServiceAuthenticationWithSharedAccessPolicyToken : string * string -&gt; Microsoft.Azure.Devices.ServiceAuthenticationWithSharedAccessPolicyToken" Usage="new Microsoft.Azure.Devices.ServiceAuthenticationWithSharedAccessPolicyToken (policyName, token)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="token" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="policyName"><span data-ttu-id="336fd-102">使用する共有アクセス ポリシーの名前です。</span><span class="sxs-lookup"><span data-stu-id="336fd-102">Name of the shared access policy to use.</span></span></param>
        <param name="token"><span data-ttu-id="336fd-103">共有アクセス ポリシーに関連付けられたトークンです。</span><span class="sxs-lookup"><span data-stu-id="336fd-103">Token associated with the shared access policy.</span></span></param>
        <summary>
            <span data-ttu-id="336fd-104"><see cref="T:Microsoft.Azure.Devices.ServiceAuthenticationWithSharedAccessPolicyToken" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="336fd-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Devices.ServiceAuthenticationWithSharedAccessPolicyToken" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PolicyName">
      <MemberSignature Language="C#" Value="public string PolicyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PolicyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.ServiceAuthenticationWithSharedAccessPolicyToken.PolicyName" />
      <MemberSignature Language="VB.NET" Value="Public Property PolicyName As String" />
      <MemberSignature Language="F#" Value="member this.PolicyName : string with get, set" Usage="Microsoft.Azure.Devices.ServiceAuthenticationWithSharedAccessPolicyToken.PolicyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
    <Member MemberName="Populate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.IotHubConnectionStringBuilder Populate (Microsoft.Azure.Devices.IotHubConnectionStringBuilder iotHubConnectionStringBuilder);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Devices.IotHubConnectionStringBuilder Populate(class Microsoft.Azure.Devices.IotHubConnectionStringBuilder iotHubConnectionStringBuilder) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ServiceAuthenticationWithSharedAccessPolicyToken.Populate(Microsoft.Azure.Devices.IotHubConnectionStringBuilder)" />
      <MemberSignature Language="F#" Value="abstract member Populate : Microsoft.Azure.Devices.IotHubConnectionStringBuilder -&gt; Microsoft.Azure.Devices.IotHubConnectionStringBuilder&#xA;override this.Populate : Microsoft.Azure.Devices.IotHubConnectionStringBuilder -&gt; Microsoft.Azure.Devices.IotHubConnectionStringBuilder" Usage="serviceAuthenticationWithSharedAccessPolicyToken.Populate iotHubConnectionStringBuilder" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Devices.IAuthenticationMethod.Populate(Microsoft.Azure.Devices.IotHubConnectionStringBuilder)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.IotHubConnectionStringBuilder</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="iotHubConnectionStringBuilder" Type="Microsoft.Azure.Devices.IotHubConnectionStringBuilder" />
      </Parameters>
      <Docs>
        <param name="iotHubConnectionStringBuilder">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Token">
      <MemberSignature Language="C#" Value="public string Token { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Token" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.ServiceAuthenticationWithSharedAccessPolicyToken.Token" />
      <MemberSignature Language="VB.NET" Value="Public Property Token As String" />
      <MemberSignature Language="F#" Value="member this.Token : string with get, set" Usage="Microsoft.Azure.Devices.ServiceAuthenticationWithSharedAccessPolicyToken.Token" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
  </Members>
</Type>