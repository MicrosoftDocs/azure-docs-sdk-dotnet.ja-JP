<Type Name="ServiceProperties" FullName="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties">
  <TypeSignature Language="C#" Value="public sealed class ServiceProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceProperties" />
  <TypeSignature Language="F#" Value="type ServiceProperties = class" />
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
            <span data-ttu-id="0dbfc-101">クラウド ストレージ サービスに関連するプロパティのセットを表すクラスです。</span><span class="sxs-lookup"><span data-stu-id="0dbfc-101">Class representing a set of properties pertaining to a cloud storage service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties.#ctor" />
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
            <span data-ttu-id="0dbfc-102">ServiceProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0dbfc-102">Initializes a new instance of the ServiceProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceProperties (Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingProperties logging = null, Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties hourMetrics = null, Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties minuteMetrics = null, Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsProperties cors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingProperties logging, class Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties hourMetrics, class Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties minuteMetrics, class Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsProperties cors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties.#ctor(Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingProperties,Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties,Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties,Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional logging As LoggingProperties = null, Optional hourMetrics As MetricsProperties = null, Optional minuteMetrics As MetricsProperties = null, Optional cors As CorsProperties = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingProperties * Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties * Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties * Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsProperties -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" Usage="new Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties (logging, hourMetrics, minuteMetrics, cors)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="logging" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingProperties" />
        <Parameter Name="hourMetrics" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties" />
        <Parameter Name="minuteMetrics" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties" />
        <Parameter Name="cors" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsProperties" />
      </Parameters>
      <Docs>
        <param name="logging">To be added.</param>
        <param name="hourMetrics">To be added.</param>
        <param name="minuteMetrics">To be added.</param>
        <param name="cors">To be added.</param>
        <summary>
            <span data-ttu-id="0dbfc-103">ServiceProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0dbfc-103">Initializes a new instance of the ServiceProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Cors">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsProperties Cors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsProperties Cors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties.Cors" />
      <MemberSignature Language="VB.NET" Value="Public Property Cors As CorsProperties" />
      <MemberSignature Language="F#" Value="member this.Cors : Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsProperties with get, set" Usage="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties.Cors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0dbfc-104">取得またはクロス オリジン リソース共有 (CORS) のプロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="0dbfc-104">Gets or sets the Cross Origin Resource Sharing (CORS) properties.</span></span>
            </summary>
        <value><span data-ttu-id="0dbfc-105">CORS のプロパティです。</span><span class="sxs-lookup"><span data-stu-id="0dbfc-105">The CORS properties.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultServiceVersion">
      <MemberSignature Language="C#" Value="public string DefaultServiceVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultServiceVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties.DefaultServiceVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultServiceVersion As String" />
      <MemberSignature Language="F#" Value="member this.DefaultServiceVersion : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties.DefaultServiceVersion" />
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
            <span data-ttu-id="0dbfc-106">取得または既定のサービス バージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="0dbfc-106">Gets or sets the default service version.</span></span>
            </summary>
        <value><span data-ttu-id="0dbfc-107">既定のサービスのバージョン識別子です。</span><span class="sxs-lookup"><span data-stu-id="0dbfc-107">The default service version identifier.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HourMetrics">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties HourMetrics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties HourMetrics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties.HourMetrics" />
      <MemberSignature Language="VB.NET" Value="Public Property HourMetrics As MetricsProperties" />
      <MemberSignature Language="F#" Value="member this.HourMetrics : Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties with get, set" Usage="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties.HourMetrics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0dbfc-108">取得または時間メトリックのプロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="0dbfc-108">Gets or sets the hour metrics properties.</span></span>
            </summary>
        <value><span data-ttu-id="0dbfc-109">メトリックのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="0dbfc-109">The metrics properties.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Logging">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingProperties Logging { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingProperties Logging" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties.Logging" />
      <MemberSignature Language="VB.NET" Value="Public Property Logging As LoggingProperties" />
      <MemberSignature Language="F#" Value="member this.Logging : Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingProperties with get, set" Usage="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties.Logging" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0dbfc-110">取得またはログのプロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="0dbfc-110">Gets or sets the logging properties.</span></span>
            </summary>
        <value><span data-ttu-id="0dbfc-111">ログのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="0dbfc-111">The logging properties.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinuteMetrics">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties MinuteMetrics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties MinuteMetrics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties.MinuteMetrics" />
      <MemberSignature Language="VB.NET" Value="Public Property MinuteMetrics As MetricsProperties" />
      <MemberSignature Language="F#" Value="member this.MinuteMetrics : Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties with get, set" Usage="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties.MinuteMetrics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.MetricsProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0dbfc-112">取得または分単位のメトリックのプロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="0dbfc-112">Gets or sets the minute metrics properties.</span></span>
            </summary>
        <value><span data-ttu-id="0dbfc-113">分単位のメトリックのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="0dbfc-113">The minute metrics properties.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>