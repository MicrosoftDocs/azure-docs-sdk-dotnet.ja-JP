<Type Name="ConnectionStatusChangesHandler" FullName="Microsoft.Azure.Devices.Client.ConnectionStatusChangesHandler">
  <TypeSignature Language="C#" Value="public delegate void ConnectionStatusChangesHandler(ConnectionStatus status, ConnectionStatusChangeReason reason);" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ConnectionStatusChangesHandler extends System.MulticastDelegate" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.ConnectionStatusChangesHandler" />
  <TypeSignature Language="VB.NET" Value="Public Delegate Sub ConnectionStatusChangesHandler(status As ConnectionStatus, reason As ConnectionStatusChangeReason)" />
  <TypeSignature Language="F#" Value="type ConnectionStatusChangesHandler = delegate of ConnectionStatus * ConnectionStatusChangeReason -&gt; unit" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Delegate</BaseTypeName>
  </Base>
  <Parameters>
    <Parameter Name="status" Type="Microsoft.Azure.Devices.Client.ConnectionStatus" />
    <Parameter Name="reason" Type="Microsoft.Azure.Devices.Client.ConnectionStatusChangeReason" />
  </Parameters>
  <ReturnValue>
    <ReturnType>System.Void</ReturnType>
  </ReturnValue>
  <Docs>
    <param name="status">更新後の接続状態</param>
    <param name="reason">接続状態の変更の理由</param>
    <summary>
            デリゲートの接続の状態が変更されました。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
</Type>