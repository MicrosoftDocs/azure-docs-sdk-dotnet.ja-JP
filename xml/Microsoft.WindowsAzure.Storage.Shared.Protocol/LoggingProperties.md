<Type Name="LoggingProperties" FullName="Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingProperties">
  <TypeSignature Language="C#" Value="public sealed class LoggingProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit LoggingProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingProperties" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class LoggingProperties" />
  <TypeSignature Language="F#" Value="type LoggingProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e1b9c-101">ログに関連するサービスのプロパティを表すクラスです。</span><span class="sxs-lookup"><span data-stu-id="e1b9c-101">Class representing the service properties pertaining to logging.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LoggingProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e1b9c-102">LoggingProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e1b9c-102">Initializes a new instance of the LoggingProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LoggingProperties (string version);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingProperties.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (version As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingProperties : string -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingProperties" Usage="new Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingProperties version" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="version" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="version">To be added.</param>
        <summary>
            <span data-ttu-id="e1b9c-103">LoggingProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e1b9c-103">Initializes a new instance of the LoggingProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoggingOperations">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations LoggingOperations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations LoggingOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingProperties.LoggingOperations" />
      <MemberSignature Language="VB.NET" Value="Public Property LoggingOperations As LoggingOperations" />
      <MemberSignature Language="F#" Value="member this.LoggingOperations : Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations with get, set" Usage="Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingProperties.LoggingOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1b9c-104">取得またはログ記録の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="e1b9c-104">Gets or sets the state of logging.</span></span>
            </summary>
        <value><span data-ttu-id="e1b9c-105">組み合わせた<see cref="P:Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingProperties.LoggingOperations" />ログに記録される操作を記述するフラグ。</span><span class="sxs-lookup"><span data-stu-id="e1b9c-105">A combination of <see cref="P:Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingProperties.LoggingOperations" /> flags describing the operations that are logged.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionDays">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RetentionDays { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RetentionDays" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingProperties.RetentionDays" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionDays As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RetentionDays : Nullable&lt;int&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingProperties.RetentionDays" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1b9c-106">取得またはログの保持ポリシーを設定します。</span><span class="sxs-lookup"><span data-stu-id="e1b9c-106">Gets or sets the logging retention policy.</span></span>
            </summary>
        <value><span data-ttu-id="e1b9c-107">ログを保持する日数。</span><span class="sxs-lookup"><span data-stu-id="e1b9c-107">The number of days to retain the logs.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingProperties.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingProperties.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1b9c-108">取得または分析サービスのバージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="e1b9c-108">Gets or sets the version of the analytics service.</span></span>
            </summary>
        <value><span data-ttu-id="e1b9c-109">サービスのバージョンを識別する文字列。</span><span class="sxs-lookup"><span data-stu-id="e1b9c-109">A string identifying the version of the service.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>