<Type Name="IHybridConnectionStatus" FullName="Microsoft.ServiceBus.IHybridConnectionStatus">
  <TypeSignature Language="C#" Value="public interface IHybridConnectionStatus" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IHybridConnectionStatus" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.IHybridConnectionStatus" />
  <TypeSignature Language="VB.NET" Value="Public Interface IHybridConnectionStatus" />
  <TypeSignature Language="F#" Value="type IHybridConnectionStatus = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="edd8c-101">ハイブリッド接続のチャネルの現在の接続状態へのアクセスを提供します。</span><span class="sxs-lookup"><span data-stu-id="edd8c-101">Provides access to the current connection state of a hybrid connection channel.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ConnectionState">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.HybridConnectionState ConnectionState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.HybridConnectionState ConnectionState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.IHybridConnectionStatus.ConnectionState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConnectionState As HybridConnectionState" />
      <MemberSignature Language="F#" Value="member this.ConnectionState : Microsoft.ServiceBus.HybridConnectionState" Usage="Microsoft.ServiceBus.IHybridConnectionStatus.ConnectionState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.HybridConnectionState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="edd8c-102">ハイブリッド接続の現在の接続状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="edd8c-102">Gets the current connection state of the hybrid connection.</span></span> </summary>
        <value><span data-ttu-id="edd8c-103">返します<see cref="T:Microsoft.ServiceBus.HybridConnectionState" />です。接続状態が含まれています。</span><span class="sxs-lookup"><span data-stu-id="edd8c-103">Returns <see cref="T:Microsoft.ServiceBus.HybridConnectionState" />.Contains the connection state.</span></span> </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionStateChanged">
      <MemberSignature Language="C#" Value="event EventHandler&lt;Microsoft.ServiceBus.HybridConnectionStateChangedArgs&gt; ConnectionStateChanged;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceBus.HybridConnectionStateChangedArgs&gt; ConnectionStateChanged" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceBus.IHybridConnectionStatus.ConnectionStateChanged" />
      <MemberSignature Language="VB.NET" Value="Event ConnectionStateChanged As EventHandler(Of HybridConnectionStateChangedArgs) " />
      <MemberSignature Language="F#" Value="member this.ConnectionStateChanged : EventHandler&lt;Microsoft.ServiceBus.HybridConnectionStateChangedArgs&gt; " Usage="member this.ConnectionStateChanged : System.EventHandler&lt;Microsoft.ServiceBus.HybridConnectionStateChangedArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceBus.HybridConnectionStateChangedArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="edd8c-104">接続状態が変更されたときに発生します。</span><span class="sxs-lookup"><span data-stu-id="edd8c-104">Occurs when the connection state changes.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>