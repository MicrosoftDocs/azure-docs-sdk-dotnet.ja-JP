<Type Name="DeviceAlreadyExistsException" FullName="Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException">
  <TypeSignature Language="C#" Value="public sealed class DeviceAlreadyExistsException : Microsoft.Azure.Devices.Client.Exceptions.IotHubException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit DeviceAlreadyExistsException extends Microsoft.Azure.Devices.Client.Exceptions.IotHubException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeviceAlreadyExistsException&#xA;Inherits IotHubException" />
  <TypeSignature Language="F#" Value="type DeviceAlreadyExistsException = class&#xA;    inherit IotHubException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Devices.Client.Exceptions.IotHubException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            失敗した場合、デバイスの作成に既に存在するためにスローされる例外。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceAlreadyExistsException (string deviceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string deviceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (deviceId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException : string -&gt; Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException deviceId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceId">既に存在するデバイスの識別子です。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException" />既に既存のデバイスの識別子を含むメッセージ文字列を持つクラス。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceAlreadyExistsException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info">スローされた例外に関する、シリアル化されたオブジェクト データを保持するオブジェクト。</param>
        <param name="context">ソースまたは転送先に関するコンテキスト情報を含むオブジェクトです。</param>
        <summary>
            指定したシリアル化情報とコンテキスト情報を使用して、<see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceAlreadyExistsException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException : string * Exception -&gt; Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException (message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">エラーの説明。 メッセージの内容は、ユーザーが理解できる内容にします。 このコンストラクターの呼び出し元は、この文字列が現在のシステムのカルチャに合わせてローカライズ済みであることを確認しておく必要があります。</param>
        <param name="innerException">現在の例外の原因となった例外</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException" />メッセージ文字列を既に既存のデバイスおよびこの例外の原因となった内部例外への参照のデバイス識別子に設定しています。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>