<Type Name="IConnectionStatus" FullName="Microsoft.ServiceBus.IConnectionStatus">
  <TypeSignature Language="C#" Value="public interface IConnectionStatus" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IConnectionStatus" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.IConnectionStatus" />
  <TypeSignature Language="VB.NET" Value="Public Interface IConnectionStatus" />
  <TypeSignature Language="F#" Value="type IConnectionStatus = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="62164-101">一方向の接続の現在の状態について説明します。</span><span class="sxs-lookup"><span data-stu-id="62164-101">Describes the current status of a one-way connection.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Connecting">
      <MemberSignature Language="C#" Value="event EventHandler Connecting;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler Connecting" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceBus.IConnectionStatus.Connecting" />
      <MemberSignature Language="VB.NET" Value="Event Connecting As EventHandler " />
      <MemberSignature Language="F#" Value="member this.Connecting : EventHandler " Usage="member this.Connecting : System.EventHandler " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="62164-102">接続が確立されると発生します。</span><span class="sxs-lookup"><span data-stu-id="62164-102">Occurs when the connection is being established.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsOnline">
      <MemberSignature Language="C#" Value="public bool IsOnline { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsOnline" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.IConnectionStatus.IsOnline" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsOnline As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsOnline : bool" Usage="Microsoft.ServiceBus.IConnectionStatus.IsOnline" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="62164-103">接続がオンラインかどうかを決定する値を取得します。</span><span class="sxs-lookup"><span data-stu-id="62164-103">Gets a value that determines whether the connection is online.</span></span></summary>
        <value><span data-ttu-id="62164-104">接続がアライブとオンライン以外の場合は true現在のネットワークの場所から Azure サービス バスに接続されていない場合は false。</span><span class="sxs-lookup"><span data-stu-id="62164-104">true if the connection is alive and online; false if there is no connectivity towards the Azure Service Bus from the current network location.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastError">
      <MemberSignature Language="C#" Value="public Exception LastError { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Exception LastError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.IConnectionStatus.LastError" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastError As Exception" />
      <MemberSignature Language="F#" Value="member this.LastError : Exception" Usage="Microsoft.ServiceBus.IConnectionStatus.LastError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="62164-105">オフラインの状態からの接続を再確立する際に発生した最後のエラーを取得します。</span><span class="sxs-lookup"><span data-stu-id="62164-105">Retrieves the last error encountered when trying to reestablish the connection from the offline state.</span></span></summary>
        <value><span data-ttu-id="62164-106">返します、<see cref="T:System.Exception" />最後のエラーを格納しています。</span><span class="sxs-lookup"><span data-stu-id="62164-106">Returns a <see cref="T:System.Exception" /> that contains the last error.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Offline">
      <MemberSignature Language="C#" Value="event EventHandler Offline;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler Offline" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceBus.IConnectionStatus.Offline" />
      <MemberSignature Language="VB.NET" Value="Event Offline As EventHandler " />
      <MemberSignature Language="F#" Value="member this.Offline : EventHandler " Usage="member this.Offline : System.EventHandler " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="62164-107">接続がオフラインになったときに発生します。</span><span class="sxs-lookup"><span data-stu-id="62164-107">Occurs when the connection goes offline.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Online">
      <MemberSignature Language="C#" Value="event EventHandler Online;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler Online" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceBus.IConnectionStatus.Online" />
      <MemberSignature Language="VB.NET" Value="Event Online As EventHandler " />
      <MemberSignature Language="F#" Value="member this.Online : EventHandler " Usage="member this.Online : System.EventHandler " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="62164-108">接続がオンラインになったときに発生します。</span><span class="sxs-lookup"><span data-stu-id="62164-108">Occurs when the connection comes online.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>