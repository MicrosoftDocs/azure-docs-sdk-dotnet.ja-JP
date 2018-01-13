<Type Name="PairedNamespaceOptions" FullName="Microsoft.ServiceBus.Messaging.PairedNamespaceOptions">
  <TypeSignature Language="C#" Value="public abstract class PairedNamespaceOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit PairedNamespaceOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.PairedNamespaceOptions" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class PairedNamespaceOptions" />
  <TypeSignature Language="F#" Value="type PairedNamespaceOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Service bus のメッセージングのペアの名前空間のオプションを表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected PairedNamespaceOptions (Microsoft.ServiceBus.NamespaceManager secondaryNamespaceManager, Microsoft.ServiceBus.Messaging.MessagingFactory secondaryMessagingFactory);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.NamespaceManager secondaryNamespaceManager, class Microsoft.ServiceBus.Messaging.MessagingFactory secondaryMessagingFactory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.PairedNamespaceOptions.#ctor(Microsoft.ServiceBus.NamespaceManager,Microsoft.ServiceBus.Messaging.MessagingFactory)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (secondaryNamespaceManager As NamespaceManager, secondaryMessagingFactory As MessagingFactory)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.PairedNamespaceOptions : Microsoft.ServiceBus.NamespaceManager * Microsoft.ServiceBus.Messaging.MessagingFactory -&gt; Microsoft.ServiceBus.Messaging.PairedNamespaceOptions" Usage="new Microsoft.ServiceBus.Messaging.PairedNamespaceOptions (secondaryNamespaceManager, secondaryMessagingFactory)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="secondaryNamespaceManager" Type="Microsoft.ServiceBus.NamespaceManager" />
        <Parameter Name="secondaryMessagingFactory" Type="Microsoft.ServiceBus.Messaging.MessagingFactory" />
      </Parameters>
      <Docs>
        <param name="secondaryNamespaceManager">セカンダリ名前空間マネージャー。</param>
        <param name="secondaryMessagingFactory">ペアの名前空間に関連付けられているセカンダリ メッセージング ファクトリ。</param>
        <summary><see cref="T:Microsoft.ServiceBus.Messaging.PairedNamespaceOptions" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected PairedNamespaceOptions (Microsoft.ServiceBus.NamespaceManager secondaryNamespaceManager, Microsoft.ServiceBus.Messaging.MessagingFactory secondaryMessagingFactory, TimeSpan failoverInterval);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.NamespaceManager secondaryNamespaceManager, class Microsoft.ServiceBus.Messaging.MessagingFactory secondaryMessagingFactory, valuetype System.TimeSpan failoverInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.PairedNamespaceOptions.#ctor(Microsoft.ServiceBus.NamespaceManager,Microsoft.ServiceBus.Messaging.MessagingFactory,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (secondaryNamespaceManager As NamespaceManager, secondaryMessagingFactory As MessagingFactory, failoverInterval As TimeSpan)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.PairedNamespaceOptions : Microsoft.ServiceBus.NamespaceManager * Microsoft.ServiceBus.Messaging.MessagingFactory * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.PairedNamespaceOptions" Usage="new Microsoft.ServiceBus.Messaging.PairedNamespaceOptions (secondaryNamespaceManager, secondaryMessagingFactory, failoverInterval)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="secondaryNamespaceManager" Type="Microsoft.ServiceBus.NamespaceManager" />
        <Parameter Name="secondaryMessagingFactory" Type="Microsoft.ServiceBus.Messaging.MessagingFactory" />
        <Parameter Name="failoverInterval" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="secondaryNamespaceManager">セカンダリ名前空間マネージャー。</param>
        <param name="secondaryMessagingFactory">ペアの名前空間に関連付けられているセカンダリ メッセージング ファクトリ。</param>
        <param name="failoverInterval">メッセージ<see cref="T:System.TimeSpan" />間隔フェールオーバーします。</param>
        <summary><see cref="T:Microsoft.ServiceBus.Messaging.PairedNamespaceOptions" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClearPairing">
      <MemberSignature Language="C#" Value="protected internal virtual void ClearPairing ();" />
      <MemberSignature Language="ILAsm" Value=".method familyorassemblyhidebysig newslot virtual instance void ClearPairing() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.PairedNamespaceOptions.ClearPairing" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Overridable Sub ClearPairing ()" />
      <MemberSignature Language="F#" Value="abstract member ClearPairing : unit -&gt; unit&#xA;override this.ClearPairing : unit -&gt; unit" Usage="pairedNamespaceOptions.ClearPairing " />
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
        <summary>ペアの名前空間のペアリングをディゾルブです。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverInterval">
      <MemberSignature Language="C#" Value="public TimeSpan FailoverInterval { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan FailoverInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PairedNamespaceOptions.FailoverInterval" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailoverInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.FailoverInterval : TimeSpan" Usage="Microsoft.ServiceBus.Messaging.PairedNamespaceOptions.FailoverInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>メッセージを取得します<see cref="T:System.TimeSpan" />間隔フェールオーバーします。</summary>
        <value>メッセージ<see cref="T:System.TimeSpan" />間隔フェールオーバーします。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnNotifyPrimarySendResult">
      <MemberSignature Language="C#" Value="protected abstract void OnNotifyPrimarySendResult (string path, bool success);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnNotifyPrimarySendResult(string path, bool success) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.PairedNamespaceOptions.OnNotifyPrimarySendResult(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnNotifyPrimarySendResult (path As String, success As Boolean)" />
      <MemberSignature Language="F#" Value="abstract member OnNotifyPrimarySendResult : string * bool -&gt; unit" Usage="pairedNamespaceOptions.OnNotifyPrimarySendResult (path, success)" />
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
        <param name="path">パスの文字列です。</param>
        <param name="success">true の場合は、結果を正常に送信します。それ以外の場合は false です。</param>
        <summary>結果の送信時にプライマリ メッセージングに通知します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryMessagingFactory">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessagingFactory SecondaryMessagingFactory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.MessagingFactory SecondaryMessagingFactory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PairedNamespaceOptions.SecondaryMessagingFactory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SecondaryMessagingFactory As MessagingFactory" />
      <MemberSignature Language="F#" Value="member this.SecondaryMessagingFactory : Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.PairedNamespaceOptions.SecondaryMessagingFactory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>ペアの名前空間に関連付けられているセカンダリのメッセージング ファクトリを取得します。</summary>
        <value>ペアの名前空間に関連付けられているセカンダリ メッセージング ファクトリ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryNamespaceManager">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.NamespaceManager SecondaryNamespaceManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.NamespaceManager SecondaryNamespaceManager" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PairedNamespaceOptions.SecondaryNamespaceManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SecondaryNamespaceManager As NamespaceManager" />
      <MemberSignature Language="F#" Value="member this.SecondaryNamespaceManager : Microsoft.ServiceBus.NamespaceManager" Usage="Microsoft.ServiceBus.Messaging.PairedNamespaceOptions.SecondaryNamespaceManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.NamespaceManager</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>キュー、トピック、サブスクリプションと対になった名前空間内のルールなどのエンティティを管理するオブジェクトを取得します。</summary>
        <value>キュー、トピック、サブスクリプションと対になった名前空間内のルールなどのエンティティを管理するオブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>