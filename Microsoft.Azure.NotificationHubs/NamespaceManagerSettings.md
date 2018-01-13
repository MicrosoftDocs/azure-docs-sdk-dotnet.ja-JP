<Type Name="NamespaceManagerSettings" FullName="Microsoft.Azure.NotificationHubs.NamespaceManagerSettings">
  <TypeSignature Language="C#" Value="public sealed class NamespaceManagerSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NamespaceManagerSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NamespaceManagerSettings" />
  <TypeSignature Language="F#" Value="type NamespaceManagerSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>名前空間マネージャーの設定が含まれています。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManagerSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.OperationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または GetQueue CreateQueue、やなど、すべてのサービス名前空間の管理操作の操作のタイムアウト期間を設定します。</summary>
        <value>A<see cref="T:System.TimeSpan" />タイムアウト期間を表すオブジェクト。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">null 値設定されている場合の例: null 許容 TimeSpan をスローします。</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">TimeSpan が設定されている、ゼロまたは負の値とスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="RetryPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.RetryPolicy RetryPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.RetryPolicy RetryPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.RetryPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryPolicy As RetryPolicy" />
      <MemberSignature Language="F#" Value="member this.RetryPolicy : Microsoft.Azure.NotificationHubs.RetryPolicy with get, set" Usage="Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.RetryPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.RetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または信頼性の低いアクションおよび一時的な状態の名前空間マネージャーに関連付けられている場合は、この再試行メカニズムの基本実装を設定します。</summary>
        <value>この再試行メカニズムで信頼性の低いアクションおよび名前空間マネージャーに関連付けられている一時的な問題の基本実装。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenProvider">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.TokenProvider TokenProvider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.TokenProvider TokenProvider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.TokenProvider" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenProvider As TokenProvider" />
      <MemberSignature Language="F#" Value="member this.TokenProvider : Microsoft.Azure.NotificationHubs.TokenProvider with get, set" Usage="Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.TokenProvider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはセキュリティ トークン プロバイダーを設定します。</summary>
        <value>セキュリティ トークン プロバイダー。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>