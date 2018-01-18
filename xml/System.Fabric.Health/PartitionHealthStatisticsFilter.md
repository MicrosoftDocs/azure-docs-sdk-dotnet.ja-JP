<Type Name="PartitionHealthStatisticsFilter" FullName="System.Fabric.Health.PartitionHealthStatisticsFilter">
  <TypeSignature Language="C#" Value="public sealed class PartitionHealthStatisticsFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PartitionHealthStatisticsFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.PartitionHealthStatisticsFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PartitionHealthStatisticsFilter" />
  <TypeSignature Language="F#" Value="type PartitionHealthStatisticsFilter = class" />
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
      <para><span data-ttu-id="f2937-101">フィルターを表す<see cref="T:System.Fabric.Health.HealthStatistics" />です。</span><span class="sxs-lookup"><span data-stu-id="f2937-101">Represents the filter for <see cref="T:System.Fabric.Health.HealthStatistics" />.</span></span></para>
    </summary>
    <remarks><span data-ttu-id="f2937-102">使用できるフィルター<see cref="T:System.Fabric.Description.PartitionHealthQueryDescription" />正常性の統計情報の一部として返されるかどうかを指定する<see cref="T:System.Fabric.Health.PartitionHealth" />です。</span><span class="sxs-lookup"><span data-stu-id="f2937-102">The filter can be used in <see cref="T:System.Fabric.Description.PartitionHealthQueryDescription" /> to specify whether the health statistics should be returned as part of <see cref="T:System.Fabric.Health.PartitionHealth" />.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PartitionHealthStatisticsFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.PartitionHealthStatisticsFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="f2937-103"><see cref="T:System.Fabric.Health.PartitionHealthStatisticsFilter" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f2937-103">Initializes a new instance of the <see cref="T:System.Fabric.Health.PartitionHealthStatisticsFilter" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExcludeHealthStatistics">
      <MemberSignature Language="C#" Value="public bool ExcludeHealthStatistics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ExcludeHealthStatistics" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionHealthStatisticsFilter.ExcludeHealthStatistics" />
      <MemberSignature Language="VB.NET" Value="Public Property ExcludeHealthStatistics As Boolean" />
      <MemberSignature Language="F#" Value="member this.ExcludeHealthStatistics : bool with get, set" Usage="System.Fabric.Health.PartitionHealthStatisticsFilter.ExcludeHealthStatistics" />
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
            <span data-ttu-id="f2937-104">取得または状態の統計をクエリの結果に含める必要があるかどうかを示すフラグを設定します。</span><span class="sxs-lookup"><span data-stu-id="f2937-104">Gets or sets a flag that indicates whether the health statistics should be included in query result.</span></span>
            </summary>
        <value><span data-ttu-id="f2937-105">状態の統計をクエリの結果に含める必要があるかどうかを示すフラグです。</span><span class="sxs-lookup"><span data-stu-id="f2937-105">A flag that indicates whether the health statistics should be included in query result.</span></span></value>
        <remarks>
          <para>
            <span data-ttu-id="f2937-106">ExcludeHealthStatistics に設定されている場合<languageKeyword>true</languageKeyword>状態の統計はクエリ結果の一部として返されません。</span><span class="sxs-lookup"><span data-stu-id="f2937-106">If ExcludeHealthStatistics is set to <languageKeyword>true</languageKeyword>, the health statistics are not returned as part of the query result.</span></span>
            <span data-ttu-id="f2937-107">それ以外の場合、クエリ結果に含まれますパーティション正常性の統計情報、レプリカの数が、に関する情報を含む<see cref="F:System.Fabric.Health.HealthState.Ok" />、 <see cref="F:System.Fabric.Health.HealthState.Warning" />、および<see cref="F:System.Fabric.Health.HealthState.Error" />状態です。</span><span class="sxs-lookup"><span data-stu-id="f2937-107">Otherwise, the query result includes the partition health statistics, which contains information about how many replicas are in <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, and <see cref="F:System.Fabric.Health.HealthState.Error" /> state.</span></span>
            <span data-ttu-id="f2937-108">既定値は<languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="f2937-108">Defaults to <languageKeyword>false</languageKeyword>.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.PartitionHealthStatisticsFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="partitionHealthStatisticsFilter.ToString " />
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
            <span data-ttu-id="f2937-109">フィルターの文字列表現を返します。</span><span class="sxs-lookup"><span data-stu-id="f2937-109">Returns a string representation of the filter.</span></span>
            </summary>
        <returns><span data-ttu-id="f2937-110">フィルターの文字列形式。</span><span class="sxs-lookup"><span data-stu-id="f2937-110">A string representation of the filter.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>