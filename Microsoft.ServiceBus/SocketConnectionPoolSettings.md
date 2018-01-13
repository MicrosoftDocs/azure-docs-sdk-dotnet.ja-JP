<Type Name="SocketConnectionPoolSettings" FullName="Microsoft.ServiceBus.SocketConnectionPoolSettings">
  <TypeSignature Language="C#" Value="public sealed class SocketConnectionPoolSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SocketConnectionPoolSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.SocketConnectionPoolSettings" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SocketConnectionPoolSettings" />
  <TypeSignature Language="F#" Value="type SocketConnectionPoolSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>ソケット接続プールの動作を制御するプロパティを表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GroupName">
      <MemberSignature Language="C#" Value="public string GroupName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GroupName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.SocketConnectionPoolSettings.GroupName" />
      <MemberSignature Language="VB.NET" Value="Public Property GroupName As String" />
      <MemberSignature Language="F#" Value="member this.GroupName : string with get, set" Usage="Microsoft.ServiceBus.SocketConnectionPoolSettings.GroupName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはソケット接続プールのグループ名を設定します。</summary>
        <value>ソケット接続プールのグループ名。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IdleTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan IdleTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan IdleTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.SocketConnectionPoolSettings.IdleTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property IdleTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.IdleTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.SocketConnectionPoolSettings.IdleTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>接続プール内の接続が切断されるまでの最大アイドル時間を取得または設定します。</summary>
        <value>時間の最大値、できる接続アイドル接続プールに切断されるまでです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan LeaseTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LeaseTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.SocketConnectionPoolSettings.LeaseTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LeaseTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LeaseTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.SocketConnectionPoolSettings.LeaseTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>アクティブな接続が終了されるまでの期間を取得または設定します。</summary>
        <value>ソケット接続が閉じられるまでの期間です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxOutboundConnectionsPerEndpoint">
      <MemberSignature Language="C#" Value="public int MaxOutboundConnectionsPerEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxOutboundConnectionsPerEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.SocketConnectionPoolSettings.MaxOutboundConnectionsPerEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxOutboundConnectionsPerEndpoint As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxOutboundConnectionsPerEndpoint : int with get, set" Usage="Microsoft.ServiceBus.SocketConnectionPoolSettings.MaxOutboundConnectionsPerEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>接続プールにキャッシュされている各エンドポイントの発信接続の最大数を取得または設定します。</summary>
        <value>接続プールにキャッシュされている各エンドポイントの発信接続の最大数。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>