<Type Name="ApplicationHealthStatisticsFilter" FullName="System.Fabric.Health.ApplicationHealthStatisticsFilter">
  <TypeSignature Language="C#" Value="public sealed class ApplicationHealthStatisticsFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationHealthStatisticsFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ApplicationHealthStatisticsFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationHealthStatisticsFilter" />
  <TypeSignature Language="F#" Value="type ApplicationHealthStatisticsFilter = class" />
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
      <para><span data-ttu-id="62d25-101">フィルターを表す<see cref="T:System.Fabric.Health.HealthStatistics" />です。</span><span class="sxs-lookup"><span data-stu-id="62d25-101">Represents the filter for <see cref="T:System.Fabric.Health.HealthStatistics" />.</span></span></para>
    </summary>
    <remarks><span data-ttu-id="62d25-102">使用できるフィルター<see cref="T:System.Fabric.Description.ApplicationHealthQueryDescription" />正常性の統計情報の一部として返されるかどうかを指定する<see cref="T:System.Fabric.Health.ApplicationHealth" />です。</span><span class="sxs-lookup"><span data-stu-id="62d25-102">The filter can be used in <see cref="T:System.Fabric.Description.ApplicationHealthQueryDescription" /> to specify whether the health statistics should be returned as part of <see cref="T:System.Fabric.Health.ApplicationHealth" />.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationHealthStatisticsFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealthStatisticsFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="62d25-103"><see cref="T:System.Fabric.Health.ApplicationHealthStatisticsFilter" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="62d25-103">Initializes a new instance of the <see cref="T:System.Fabric.Health.ApplicationHealthStatisticsFilter" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExcludeHealthStatistics">
      <MemberSignature Language="C#" Value="public bool ExcludeHealthStatistics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ExcludeHealthStatistics" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthStatisticsFilter.ExcludeHealthStatistics" />
      <MemberSignature Language="VB.NET" Value="Public Property ExcludeHealthStatistics As Boolean" />
      <MemberSignature Language="F#" Value="member this.ExcludeHealthStatistics : bool with get, set" Usage="System.Fabric.Health.ApplicationHealthStatisticsFilter.ExcludeHealthStatistics" />
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
            <span data-ttu-id="62d25-104">取得または状態の統計をクエリの結果に含める必要があるかどうかを示すフラグを設定します。</span><span class="sxs-lookup"><span data-stu-id="62d25-104">Gets or sets a flag that indicates whether the health statistics should be included in query result.</span></span>
            </summary>
        <value><span data-ttu-id="62d25-105">状態の統計をクエリの結果に含める必要があるかどうかを示すフラグです。</span><span class="sxs-lookup"><span data-stu-id="62d25-105">A flag that indicates whether the health statistics should be included in query result.</span></span></value>
        <remarks>
          <para>
            <span data-ttu-id="62d25-106">ExcludeHealthStatistics に設定されている場合<languageKeyword>true</languageKeyword>状態の統計はクエリ結果の一部として返されません。</span><span class="sxs-lookup"><span data-stu-id="62d25-106">If ExcludeHealthStatistics is set to <languageKeyword>true</languageKeyword>, the health statistics are not returned as part of the query result.</span></span>
            <span data-ttu-id="62d25-107">それ以外の場合、クエリの結果には、サービスの数に関する情報を含むアプリケーション ヘルス統計情報が含まれていますが、パーティションとレプリカをこのアプリケーションの<see cref="F:System.Fabric.Health.HealthState.Ok" />、 <see cref="F:System.Fabric.Health.HealthState.Warning" />、および<see cref="F:System.Fabric.Health.HealthState.Error" />状態です。</span><span class="sxs-lookup"><span data-stu-id="62d25-107">Otherwise, the query result includes the application health statistics, which contain information about how many services, partitions and replicas of this application are in <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, and <see cref="F:System.Fabric.Health.HealthState.Error" /> state.</span></span>
            <span data-ttu-id="62d25-108">既定値は<languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="62d25-108">Defaults to <languageKeyword>false</languageKeyword>.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealthStatisticsFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applicationHealthStatisticsFilter.ToString " />
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
            <span data-ttu-id="62d25-109">フィルターの文字列表現を返します。</span><span class="sxs-lookup"><span data-stu-id="62d25-109">Returns a string representation of the filter.</span></span>
            </summary>
        <returns><span data-ttu-id="62d25-110">フィルターの文字列形式。</span><span class="sxs-lookup"><span data-stu-id="62d25-110">A string representation of the filter.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>