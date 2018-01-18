<Type Name="ServiceHealthStatisticsFilter" FullName="System.Fabric.Health.ServiceHealthStatisticsFilter">
  <TypeSignature Language="C#" Value="public sealed class ServiceHealthStatisticsFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceHealthStatisticsFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ServiceHealthStatisticsFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceHealthStatisticsFilter" />
  <TypeSignature Language="F#" Value="type ServiceHealthStatisticsFilter = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="ba166-101">フィルターを表す<see cref="T:System.Fabric.Health.HealthStatistics" />です。</span><span class="sxs-lookup"><span data-stu-id="ba166-101">Represents the filter for <see cref="T:System.Fabric.Health.HealthStatistics" />.</span></span></para>
    </summary>
    <remarks><span data-ttu-id="ba166-102">使用できるフィルター<see cref="T:System.Fabric.Description.ServiceHealthQueryDescription" />正常性の統計情報の一部として返されるかどうかを指定する<see cref="T:System.Fabric.Health.ServiceHealth" />です。</span><span class="sxs-lookup"><span data-stu-id="ba166-102">The filter can be used in <see cref="T:System.Fabric.Description.ServiceHealthQueryDescription" /> to specify whether the health statistics should be returned as part of <see cref="T:System.Fabric.Health.ServiceHealth" />.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceHealthStatisticsFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStatisticsFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="ba166-103"><see cref="T:System.Fabric.Health.ServiceHealthStatisticsFilter" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ba166-103">Initializes a new instance of the <see cref="T:System.Fabric.Health.ServiceHealthStatisticsFilter" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExcludeHealthStatistics">
      <MemberSignature Language="C#" Value="public bool ExcludeHealthStatistics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ExcludeHealthStatistics" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealthStatisticsFilter.ExcludeHealthStatistics" />
      <MemberSignature Language="VB.NET" Value="Public Property ExcludeHealthStatistics As Boolean" />
      <MemberSignature Language="F#" Value="member this.ExcludeHealthStatistics : bool with get, set" Usage="System.Fabric.Health.ServiceHealthStatisticsFilter.ExcludeHealthStatistics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba166-104">取得または状態の統計をクエリの結果に含める必要があるかどうかを示すフラグを設定します。</span><span class="sxs-lookup"><span data-stu-id="ba166-104">Gets or sets a flag that indicates whether the health statistics should be included in query result.</span></span>
            </summary>
        <value><span data-ttu-id="ba166-105">状態の統計をクエリの結果に含める必要があるかどうかを示すフラグです。</span><span class="sxs-lookup"><span data-stu-id="ba166-105">A flag that indicates whether the health statistics should be included in query result.</span></span></value>
        <remarks>
          <para>
            <span data-ttu-id="ba166-106">ExcludeHealthStatistics に設定されている場合<languageKeyword>true</languageKeyword>状態の統計はクエリ結果の一部として返されません。</span><span class="sxs-lookup"><span data-stu-id="ba166-106">If ExcludeHealthStatistics is set to <languageKeyword>true</languageKeyword>, the health statistics are not returned as part of the query result.</span></span>
            <span data-ttu-id="ba166-107">それ以外の場合、クエリの結果には、パーティションの数に関する情報を含むサービスの正常性の統計が含まれています。 および、レプリカがで<see cref="F:System.Fabric.Health.HealthState.Ok" />、 <see cref="F:System.Fabric.Health.HealthState.Warning" />、および<see cref="F:System.Fabric.Health.HealthState.Error" />状態です。</span><span class="sxs-lookup"><span data-stu-id="ba166-107">Otherwise, the query result includes the service health statistics, which contains information about how many partitions and replicas are in <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, and <see cref="F:System.Fabric.Health.HealthState.Error" /> state.</span></span>
            <span data-ttu-id="ba166-108">既定値は<languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="ba166-108">Defaults to <languageKeyword>false</languageKeyword>.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStatisticsFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="serviceHealthStatisticsFilter.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ba166-109">フィルターの文字列表現を返します。</span><span class="sxs-lookup"><span data-stu-id="ba166-109">Returns a string representation of the filter.</span></span>
            </summary>
        <returns><span data-ttu-id="ba166-110">フィルターの文字列形式。</span><span class="sxs-lookup"><span data-stu-id="ba166-110">A string representation of the filter.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>