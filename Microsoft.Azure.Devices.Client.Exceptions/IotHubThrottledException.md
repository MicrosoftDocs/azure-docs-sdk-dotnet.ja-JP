<Type Name="IotHubThrottledException" FullName="Microsoft.Azure.Devices.Client.Exceptions.IotHubThrottledException">
  <TypeSignature Language="C#" Value="public sealed class IotHubThrottledException : Microsoft.Azure.Devices.Client.Exceptions.IotHubException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit IotHubThrottledException extends Microsoft.Azure.Devices.Client.Exceptions.IotHubException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.Exceptions.IotHubThrottledException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class IotHubThrottledException&#xA;Inherits IotHubException" />
  <TypeSignature Language="F#" Value="type IotHubThrottledException = class&#xA;    inherit IotHubException" />
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
            最大数を超えているために、指数バックオフ サービスが必要な場合にスローされる例外は、アクティブな要求を許可します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IotHubThrottledException (int maximumBatchCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 maximumBatchCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.IotHubThrottledException.#ctor(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (maximumBatchCount As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.IotHubThrottledException : int -&gt; Microsoft.Azure.Devices.Client.Exceptions.IotHubThrottledException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.IotHubThrottledException maximumBatchCount" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maximumBatchCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="maximumBatchCount">アクティブな要求の最大数。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Devices.Client.Exceptions.IotHubThrottledException" />アクティブな要求の最大数を格納しているメッセージ文字列を持つクラス。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IotHubThrottledException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.IotHubThrottledException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.IotHubThrottledException : string * Exception -&gt; Microsoft.Azure.Devices.Client.Exceptions.IotHubThrottledException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.IotHubThrottledException (message, innerException)" />
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
            新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Devices.Client.Exceptions.IotHubThrottledException" />メッセージ文字列をメッセージ パラメーターおよびこの例外の原因となった内部例外への参照に設定しています。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>