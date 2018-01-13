<Type Name="PartitionManagerOptions" FullName="Microsoft.ServiceBus.Messaging.PartitionManagerOptions">
  <TypeSignature Language="C#" Value="public class PartitionManagerOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PartitionManagerOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.PartitionManagerOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class PartitionManagerOptions" />
  <TypeSignature Language="F#" Value="type PartitionManagerOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
    <AssemblyVersion>0.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>内で発生するパーティションの配布のさまざまな側面を制御するオプションを表す、<see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorHost" />インスタンス。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PartitionManagerOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.PartitionManagerOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><see cref="T:Microsoft.ServiceBus.Messaging.PartitionManagerOptions" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireInterval">
      <MemberSignature Language="C#" Value="public TimeSpan AcquireInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan AcquireInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PartitionManagerOptions.AcquireInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property AcquireInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.AcquireInterval : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.PartitionManagerOptions.AcquireInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはする間隔を設定、<see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorHost" />インスタンスのパーティションが既知のホスト インスタンス間で均等に分散するかどうかを決定するタスクが開始します。</summary>
        <value>パーティションの取得間隔です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultOptions">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.PartitionManagerOptions DefaultOptions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.ServiceBus.Messaging.PartitionManagerOptions DefaultOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PartitionManagerOptions.DefaultOptions" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property DefaultOptions As PartitionManagerOptions" />
      <MemberSignature Language="F#" Value="member this.DefaultOptions : Microsoft.ServiceBus.Messaging.PartitionManagerOptions" Usage="Microsoft.ServiceBus.Messaging.PartitionManagerOptions.DefaultOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.PartitionManagerOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>インスタンスを作成<see cref="P:Microsoft.ServiceBus.Messaging.EventProcessorHost.PartitionManagerOptions" />、次の既定値:<see cref="P:Microsoft.ServiceBus.Messaging.PartitionManagerOptions.RenewInterval" />: 10 秒です。<see cref="P:Microsoft.ServiceBus.Messaging.PartitionManagerOptions.AcquireInterval" />: 10 秒です。<see cref="P:Microsoft.ServiceBus.Messaging.PartitionManagerOptions.LeaseInterval" />: 30 秒です。 </summary>
        <value>既定のパーティション マネージャーのオプションです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseInterval">
      <MemberSignature Language="C#" Value="public TimeSpan LeaseInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LeaseInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PartitionManagerOptions.LeaseInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property LeaseInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LeaseInterval : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.PartitionManagerOptions.LeaseInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または、Event Hubs のパーティションを表す Azure Blob にリースが作成される間隔を設定します。 この時間内で、リースが更新されていない場合は、有効期限が切れるため、パーティションの所有権が別に渡します<see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorHost" />インスタンス。</summary>
        <value><see cref="T:System.TimeSpan" /> を返します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReceiveClients">
      <MemberSignature Language="C#" Value="public int MaxReceiveClients { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxReceiveClients" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PartitionManagerOptions.MaxReceiveClients" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReceiveClients As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxReceiveClients : int with get, set" Usage="Microsoft.ServiceBus.Messaging.PartitionManagerOptions.MaxReceiveClients" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewInterval">
      <MemberSignature Language="C#" Value="public TimeSpan RenewInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan RenewInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PartitionManagerOptions.RenewInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property RenewInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.RenewInterval : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.PartitionManagerOptions.RenewInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または設定によって現在保持されているパーティションのすべてのリースの更新間隔、<see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorHost" />インスタンス。</summary>
        <value>パーティションを更新する間隔。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SkipBlobContainerCreation">
      <MemberSignature Language="C#" Value="public bool SkipBlobContainerCreation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool SkipBlobContainerCreation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PartitionManagerOptions.SkipBlobContainerCreation" />
      <MemberSignature Language="VB.NET" Value="Public Property SkipBlobContainerCreation As Boolean" />
      <MemberSignature Language="F#" Value="member this.SkipBlobContainerCreation : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.PartitionManagerOptions.SkipBlobContainerCreation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>