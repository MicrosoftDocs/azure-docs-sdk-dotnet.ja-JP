<Type Name="DeviceMessageLockLostException" FullName="Microsoft.Azure.Devices.Client.Exceptions.DeviceMessageLockLostException">
  <TypeSignature Language="C#" Value="public class DeviceMessageLockLostException : Microsoft.Azure.Devices.Client.Exceptions.IotHubException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit DeviceMessageLockLostException extends Microsoft.Azure.Devices.Client.Exceptions.IotHubException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceMessageLockLostException" />
  <TypeSignature Language="VB.NET" Value="Public Class DeviceMessageLockLostException&#xA;Inherits IotHubException" />
  <TypeSignature Language="F#" Value="type DeviceMessageLockLostException = class&#xA;    inherit IotHubException" />
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
            失敗した場合、デバイスと通信する場合、接続が失われ、たとえば回復) ロック トークンが失われたためにスローされる例外。 このタイムアウトは、メッセージが abandonned 場合と同じ効果を持ちます。
            </summary>
    <remarks>
            破棄されたメッセージに re にキュー入れられたデバイスごとのキューになります、<see cref="T:Microsoft.Azure.Devices.Client.DeviceClient" />インスタンスが再び表示されます。 拒否されたメッセージはキューから削除され、デバイスにもう一度受信されません。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceMessageLockLostException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.DeviceMessageLockLostException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.DeviceMessageLockLostException : string -&gt; Microsoft.Azure.Devices.Client.Exceptions.DeviceMessageLockLostException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.DeviceMessageLockLostException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">エラーの説明。 メッセージの内容は、ユーザーが理解できる内容にします。 このコンストラクターの呼び出し元は、この文字列が現在のシステムのカルチャに合わせてローカライズ済みであることを確認しておく必要があります。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceMessageLockLostException" />見つかりませんデバイス識別子を含むメッセージ文字列を持つクラス。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceMessageLockLostException (string deviceId, Guid messageId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string deviceId, valuetype System.Guid messageId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.DeviceMessageLockLostException.#ctor(System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (deviceId As String, messageId As Guid)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.DeviceMessageLockLostException : string * Guid -&gt; Microsoft.Azure.Devices.Client.Exceptions.DeviceMessageLockLostException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.DeviceMessageLockLostException (deviceId, messageId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="messageId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="deviceId">デバイスの識別子です。</param>
        <param name="messageId">メッセージの識別子です。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceMessageLockLostException" />見つかりませんデバイス識別子を含むメッセージ文字列を持つクラス。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>