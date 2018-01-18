<Type Name="MetricsProperties" FullName="Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties">
  <TypeSignature Language="C#" Value="public sealed class MetricsProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit MetricsProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MetricsProperties" />
  <TypeSignature Language="F#" Value="type MetricsProperties = class" />
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
            <span data-ttu-id="cefe2-101">メトリックに関連するサービスのプロパティを表すクラスです。</span><span class="sxs-lookup"><span data-stu-id="cefe2-101">Class representing the service properties pertaining to metrics.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricsProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties.#ctor" />
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
            <span data-ttu-id="cefe2-102">MetricsProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="cefe2-102">Initializes a new instance of the MetricsProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricsProperties (string version);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (version As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties : string -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties" Usage="new Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties version" />
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
            <span data-ttu-id="cefe2-103">MetricsProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="cefe2-103">Initializes a new instance of the MetricsProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MetricsLevel">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsLevel MetricsLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsLevel MetricsLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties.MetricsLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property MetricsLevel As MetricsLevel" />
      <MemberSignature Language="F#" Value="member this.MetricsLevel : Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsLevel with get, set" Usage="Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties.MetricsLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsLevel</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cefe2-104">取得またはメトリックの収集の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="cefe2-104">Gets or sets the state of metrics collection.</span></span>
            </summary>
        <value><span data-ttu-id="cefe2-105">A<see cref="P:Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties.MetricsLevel" />存在する場合、収集するメトリックを示す値。</span><span class="sxs-lookup"><span data-stu-id="cefe2-105">A <see cref="P:Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties.MetricsLevel" /> value indicating which metrics to collect, if any.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionDays">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RetentionDays { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RetentionDays" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties.RetentionDays" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionDays As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RetentionDays : Nullable&lt;int&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties.RetentionDays" />
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
            <span data-ttu-id="cefe2-106">取得またはログの保持ポリシーを設定します。</span><span class="sxs-lookup"><span data-stu-id="cefe2-106">Gets or sets the logging retention policy.</span></span>
            </summary>
        <value><span data-ttu-id="cefe2-107">ログを保持する日数。</span><span class="sxs-lookup"><span data-stu-id="cefe2-107">The number of days to retain the logs.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties.Version" />
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
            <span data-ttu-id="cefe2-108">取得または分析サービスのバージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="cefe2-108">Gets or sets the version of the analytics service.</span></span>
            </summary>
        <value><span data-ttu-id="cefe2-109">サービスのバージョンを識別する文字列。</span><span class="sxs-lookup"><span data-stu-id="cefe2-109">A string identifying the version of the service.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>