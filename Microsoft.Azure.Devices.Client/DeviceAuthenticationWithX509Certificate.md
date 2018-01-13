<Type Name="DeviceAuthenticationWithX509Certificate" FullName="Microsoft.Azure.Devices.Client.DeviceAuthenticationWithX509Certificate">
  <TypeSignature Language="C#" Value="public sealed class DeviceAuthenticationWithX509Certificate : Microsoft.Azure.Devices.Client.IAuthenticationMethod" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeviceAuthenticationWithX509Certificate extends System.Object implements class Microsoft.Azure.Devices.Client.IAuthenticationMethod" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithX509Certificate" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeviceAuthenticationWithX509Certificate&#xA;Implements IAuthenticationMethod" />
  <TypeSignature Language="F#" Value="type DeviceAuthenticationWithX509Certificate = class&#xA;    interface IAuthenticationMethod" />
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
            X.509 証明書を使用する認証方法
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceAuthenticationWithX509Certificate (string deviceId, System.Security.Cryptography.X509Certificates.X509Certificate2 certificate);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string deviceId, class System.Security.Cryptography.X509Certificates.X509Certificate2 certificate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithX509Certificate.#ctor(System.String,System.Security.Cryptography.X509Certificates.X509Certificate2)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (deviceId As String, certificate As X509Certificate2)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.DeviceAuthenticationWithX509Certificate : string * System.Security.Cryptography.X509Certificates.X509Certificate2 -&gt; Microsoft.Azure.Devices.Client.DeviceAuthenticationWithX509Certificate" Usage="new Microsoft.Azure.Devices.Client.DeviceAuthenticationWithX509Certificate (deviceId, certificate)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="certificate" Type="System.Security.Cryptography.X509Certificates.X509Certificate2" />
      </Parameters>
      <Docs>
        <param name="deviceId">デバイスの識別子です。</param>
        <param name="certificate">X.509 証明書。</param>
        <summary>
            <see cref="T:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithX509Certificate" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Certificate">
      <MemberSignature Language="C#" Value="public System.Security.Cryptography.X509Certificates.X509Certificate2 Certificate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Security.Cryptography.X509Certificates.X509Certificate2 Certificate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithX509Certificate.Certificate" />
      <MemberSignature Language="VB.NET" Value="Public Property Certificate As X509Certificate2" />
      <MemberSignature Language="F#" Value="member this.Certificate : System.Security.Cryptography.X509Certificates.X509Certificate2 with get, set" Usage="Microsoft.Azure.Devices.Client.DeviceAuthenticationWithX509Certificate.Certificate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.Cryptography.X509Certificates.X509Certificate2</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このデバイスに関連付けられた X.509 証明書の設定を取得または
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceId">
      <MemberSignature Language="C#" Value="public string DeviceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeviceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithX509Certificate.DeviceId" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceId As String" />
      <MemberSignature Language="F#" Value="member this.DeviceId : string with get, set" Usage="Microsoft.Azure.Devices.Client.DeviceAuthenticationWithX509Certificate.DeviceId" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithX509Certificate.Populate(Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder)" />
      <MemberSignature Language="F#" Value="abstract member Populate : Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder -&gt; Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder&#xA;override this.Populate : Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder -&gt; Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder" Usage="deviceAuthenticationWithX509Certificate.Populate iotHubConnectionStringBuilder" />
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
  </Members>
</Type>