<Type Name="SendAvailabilityPairedNamespaceOptions" FullName="Microsoft.ServiceBus.Messaging.SendAvailabilityPairedNamespaceOptions">
  <TypeSignature Language="C#" Value="public sealed class SendAvailabilityPairedNamespaceOptions : Microsoft.ServiceBus.Messaging.PairedNamespaceOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SendAvailabilityPairedNamespaceOptions extends Microsoft.ServiceBus.Messaging.PairedNamespaceOptions" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.SendAvailabilityPairedNamespaceOptions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SendAvailabilityPairedNamespaceOptions&#xA;Inherits PairedNamespaceOptions" />
  <TypeSignature Language="F#" Value="type SendAvailabilityPairedNamespaceOptions = class&#xA;    inherit PairedNamespaceOptions" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.PairedNamespaceOptions</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>ペアの名前空間の可用性を送信するためのオプションを表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SendAvailabilityPairedNamespaceOptions (Microsoft.ServiceBus.NamespaceManager secondaryNamespaceManager, Microsoft.ServiceBus.Messaging.MessagingFactory messagingFactory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.NamespaceManager secondaryNamespaceManager, class Microsoft.ServiceBus.Messaging.MessagingFactory messagingFactory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SendAvailabilityPairedNamespaceOptions.#ctor(Microsoft.ServiceBus.NamespaceManager,Microsoft.ServiceBus.Messaging.MessagingFactory)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.SendAvailabilityPairedNamespaceOptions : Microsoft.ServiceBus.NamespaceManager * Microsoft.ServiceBus.Messaging.MessagingFactory -&gt; Microsoft.ServiceBus.Messaging.SendAvailabilityPairedNamespaceOptions" Usage="new Microsoft.ServiceBus.Messaging.SendAvailabilityPairedNamespaceOptions (secondaryNamespaceManager, messagingFactory)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="secondaryNamespaceManager" Type="Microsoft.ServiceBus.NamespaceManager" />
        <Parameter Name="messagingFactory" Type="Microsoft.ServiceBus.Messaging.MessagingFactory" />
      </Parameters>
      <Docs>
        <param name="secondaryNamespaceManager">セカンダリ名前空間マネージャー。</param>
        <param name="messagingFactory">メッセージング ファクトリ。</param>
        <summary><see cref="T:Microsoft.ServiceBus.Messaging.SendAvailabilityPairedNamespaceOptions" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SendAvailabilityPairedNamespaceOptions (Microsoft.ServiceBus.NamespaceManager secondaryNamespaceManager, Microsoft.ServiceBus.Messaging.MessagingFactory messagingFactory, int backlogQueueCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.NamespaceManager secondaryNamespaceManager, class Microsoft.ServiceBus.Messaging.MessagingFactory messagingFactory, int32 backlogQueueCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SendAvailabilityPairedNamespaceOptions.#ctor(Microsoft.ServiceBus.NamespaceManager,Microsoft.ServiceBus.Messaging.MessagingFactory,System.Int32)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.SendAvailabilityPairedNamespaceOptions : Microsoft.ServiceBus.NamespaceManager * Microsoft.ServiceBus.Messaging.MessagingFactory * int -&gt; Microsoft.ServiceBus.Messaging.SendAvailabilityPairedNamespaceOptions" Usage="new Microsoft.ServiceBus.Messaging.SendAvailabilityPairedNamespaceOptions (secondaryNamespaceManager, messagingFactory, backlogQueueCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="secondaryNamespaceManager" Type="Microsoft.ServiceBus.NamespaceManager" />
        <Parameter Name="messagingFactory" Type="Microsoft.ServiceBus.Messaging.MessagingFactory" />
        <Parameter Name="backlogQueueCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="secondaryNamespaceManager">セカンダリ名前空間マネージャー。</param>
        <param name="messagingFactory">メッセージング ファクトリ。</param>
        <param name="backlogQueueCount">バックログ キューの数。</param>
        <summary><see cref="T:Microsoft.ServiceBus.Messaging.SendAvailabilityPairedNamespaceOptions" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SendAvailabilityPairedNamespaceOptions (Microsoft.ServiceBus.NamespaceManager secondaryNamespaceManager, Microsoft.ServiceBus.Messaging.MessagingFactory messagingFactory, int backlogQueueCount, TimeSpan failoverInterval, bool enableSyphon);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.NamespaceManager secondaryNamespaceManager, class Microsoft.ServiceBus.Messaging.MessagingFactory messagingFactory, int32 backlogQueueCount, valuetype System.TimeSpan failoverInterval, bool enableSyphon) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SendAvailabilityPairedNamespaceOptions.#ctor(Microsoft.ServiceBus.NamespaceManager,Microsoft.ServiceBus.Messaging.MessagingFactory,System.Int32,System.TimeSpan,System.Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.SendAvailabilityPairedNamespaceOptions : Microsoft.ServiceBus.NamespaceManager * Microsoft.ServiceBus.Messaging.MessagingFactory * int * TimeSpan * bool -&gt; Microsoft.ServiceBus.Messaging.SendAvailabilityPairedNamespaceOptions" Usage="new Microsoft.ServiceBus.Messaging.SendAvailabilityPairedNamespaceOptions (secondaryNamespaceManager, messagingFactory, backlogQueueCount, failoverInterval, enableSyphon)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="secondaryNamespaceManager" Type="Microsoft.ServiceBus.NamespaceManager" />
        <Parameter Name="messagingFactory" Type="Microsoft.ServiceBus.Messaging.MessagingFactory" />
        <Parameter Name="backlogQueueCount" Type="System.Int32" />
        <Parameter Name="failoverInterval" Type="System.TimeSpan" />
        <Parameter Name="enableSyphon" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="secondaryNamespaceManager">セカンダリ名前空間マネージャー。</param>
        <param name="messagingFactory">メッセージング ファクトリ。</param>
        <param name="backlogQueueCount">バックログ キューの数。</param>
        <param name="failoverInterval">間隔で失敗します。</param>
        <param name="enableSyphon">サイホン; を有効にする場合は trueそれ以外の場合は false です。</param>
        <summary><see cref="T:Microsoft.ServiceBus.Messaging.SendAvailabilityPairedNamespaceOptions" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BacklogQueueCount">
      <MemberSignature Language="C#" Value="public int BacklogQueueCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 BacklogQueueCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SendAvailabilityPairedNamespaceOptions.BacklogQueueCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BacklogQueueCount As Integer" />
      <MemberSignature Language="F#" Value="member this.BacklogQueueCount : int" Usage="Microsoft.ServiceBus.Messaging.SendAvailabilityPairedNamespaceOptions.BacklogQueueCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはバックログ キューの数を設定します。</summary>
        <value>バックログ キューの数。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClearPairing">
      <MemberSignature Language="C#" Value="protected internal override void ClearPairing ();" />
      <MemberSignature Language="ILAsm" Value=".method familyorassemblyhidebysig virtual instance void ClearPairing() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SendAvailabilityPairedNamespaceOptions.ClearPairing" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Overrides Sub ClearPairing ()" />
      <MemberSignature Language="F#" Value="override this.ClearPairing : unit -&gt; unit" Usage="sendAvailabilityPairedNamespaceOptions.ClearPairing " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableSyphon">
      <MemberSignature Language="C#" Value="public bool EnableSyphon { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableSyphon" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SendAvailabilityPairedNamespaceOptions.EnableSyphon" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnableSyphon As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableSyphon : bool" Usage="Microsoft.ServiceBus.Messaging.SendAvailabilityPairedNamespaceOptions.EnableSyphon" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはサイホンがこのインスタンスに対して有効にするかどうかを設定します。</summary>
        <value>このインスタンスに対して、サイホンが有効になっている場合は true。それ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MarkPathHealthy">
      <MemberSignature Language="C#" Value="public void MarkPathHealthy (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void MarkPathHealthy(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SendAvailabilityPairedNamespaceOptions.MarkPathHealthy(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub MarkPathHealthy (path As String)" />
      <MemberSignature Language="F#" Value="member this.MarkPathHealthy : string -&gt; unit" Usage="sendAvailabilityPairedNamespaceOptions.MarkPathHealthy path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">マークへのパス。</param>
        <summary>正常であるパスをマークします。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnNotifyPrimarySendResult">
      <MemberSignature Language="C#" Value="protected override void OnNotifyPrimarySendResult (string path, bool success);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnNotifyPrimarySendResult(string path, bool success) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SendAvailabilityPairedNamespaceOptions.OnNotifyPrimarySendResult(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnNotifyPrimarySendResult (path As String, success As Boolean)" />
      <MemberSignature Language="F#" Value="override this.OnNotifyPrimarySendResult : string * bool -&gt; unit" Usage="sendAvailabilityPairedNamespaceOptions.OnNotifyPrimarySendResult (path, success)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="success" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="path">To be added.</param>
        <param name="success">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PingPrimaryInterval">
      <MemberSignature Language="C#" Value="public TimeSpan PingPrimaryInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan PingPrimaryInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SendAvailabilityPairedNamespaceOptions.PingPrimaryInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property PingPrimaryInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.PingPrimaryInterval : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.SendAvailabilityPairedNamespaceOptions.PingPrimaryInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または ping の間隔を設定します。</summary>
        <value>Ping の間隔です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>