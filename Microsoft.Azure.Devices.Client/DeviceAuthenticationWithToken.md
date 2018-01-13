<Type Name="DeviceAuthenticationWithToken" FullName="Microsoft.Azure.Devices.Client.DeviceAuthenticationWithToken">
  <TypeSignature Language="C#" Value="public sealed class DeviceAuthenticationWithToken : Microsoft.Azure.Devices.Client.IAuthenticationMethod" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeviceAuthenticationWithToken extends System.Object implements class Microsoft.Azure.Devices.Client.IAuthenticationMethod" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithToken" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeviceAuthenticationWithToken&#xA;Implements IAuthenticationMethod" />
  <TypeSignature Language="F#" Value="type DeviceAuthenticationWithToken = class&#xA;    interface IAuthenticationMethod" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Devices.Client.IAuthenticationMethod</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            共有アクセス署名トークンを使用する認証方法です。 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceAuthenticationWithToken (string deviceId, string token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string deviceId, string token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithToken.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (deviceId As String, token As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.DeviceAuthenticationWithToken : string * string -&gt; Microsoft.Azure.Devices.Client.DeviceAuthenticationWithToken" Usage="new Microsoft.Azure.Devices.Client.DeviceAuthenticationWithToken (deviceId, token)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="token" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceId">デバイスの識別子です。</param>
        <param name="token">セキュリティ トークンです。</param>
        <summary>
            <see cref="T:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithToken" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceId">
      <MemberSignature Language="C#" Value="public string DeviceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeviceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithToken.DeviceId" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceId As String" />
      <MemberSignature Language="F#" Value="member this.DeviceId : string with get, set" Usage="Microsoft.Azure.Devices.Client.DeviceAuthenticationWithToken.DeviceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバイス識別子を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Populate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder Populate (Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder iotHubConnectionStringBuilder);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder Populate(class Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder iotHubConnectionStringBuilder) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithToken.Populate(Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder)" />
      <MemberSignature Language="F#" Value="abstract member Populate : Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder -&gt; Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder&#xA;override this.Populate : Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder -&gt; Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder" Usage="deviceAuthenticationWithToken.Populate iotHubConnectionStringBuilder" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Devices.Client.IAuthenticationMethod.Populate(Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="iotHubConnectionStringBuilder" Type="Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder" />
      </Parameters>
      <Docs>
        <param name="iotHubConnectionStringBuilder">インスタンスを設定します。</param>
        <summary>
            追加、<see cref="T:Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder" />インスタンスが現在のインスタンスのプロパティに基づきます。
            </summary>
        <returns>設定された<see cref="T:Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder" />インスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Token">
      <MemberSignature Language="C#" Value="public string Token { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Token" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithToken.Token" />
      <MemberSignature Language="VB.NET" Value="Public Property Token As String" />
      <MemberSignature Language="F#" Value="member this.Token : string with get, set" Usage="Microsoft.Azure.Devices.Client.DeviceAuthenticationWithToken.Token" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバイスに関連付けられているセキュリティ トークンを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>