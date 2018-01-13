<Type Name="ClusterHealthStatisticsFilter" FullName="System.Fabric.Health.ClusterHealthStatisticsFilter">
  <TypeSignature Language="C#" Value="public sealed class ClusterHealthStatisticsFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ClusterHealthStatisticsFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ClusterHealthStatisticsFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ClusterHealthStatisticsFilter" />
  <TypeSignature Language="F#" Value="type ClusterHealthStatisticsFilter = class" />
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
      <para>フィルターを表す<see cref="T:System.Fabric.Health.HealthStatistics" />です。</para>
    </summary>
    <remarks>使用できるフィルター<see cref="T:System.Fabric.Description.ClusterHealthQueryDescription" />正常性の統計情報の一部として返されるかどうかを指定する<see cref="T:System.Fabric.Health.ClusterHealth" />です。</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterHealthStatisticsFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ClusterHealthStatisticsFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Health.ClusterHealthStatisticsFilter" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExcludeHealthStatistics">
      <MemberSignature Language="C#" Value="public bool ExcludeHealthStatistics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ExcludeHealthStatistics" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealthStatisticsFilter.ExcludeHealthStatistics" />
      <MemberSignature Language="VB.NET" Value="Public Property ExcludeHealthStatistics As Boolean" />
      <MemberSignature Language="F#" Value="member this.ExcludeHealthStatistics : bool with get, set" Usage="System.Fabric.Health.ClusterHealthStatisticsFilter.ExcludeHealthStatistics" />
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
            取得または状態の統計をクエリの結果に含める必要があるかどうかを示すフラグを設定します。
            </summary>
        <value>状態の統計をクエリの結果に含める必要があるかどうかを示すフラグです。</value>
        <remarks>
          <para>
            ExcludeHealthStatistics に設定されている場合<languageKeyword>true</languageKeyword>状態の統計はクエリ結果の一部として返されません。
            それ以外の場合、クエリの結果には、クラスターの状態の統計が含まれています。
            統計の数を含む、エンティティの種類ごとのクラスター内のエンティティの数を示しています<see cref="F:System.Fabric.Health.HealthState.Ok" />、 <see cref="F:System.Fabric.Health.HealthState.Warning" />、および<see cref="F:System.Fabric.Health.HealthState.Error" />状態です。
            既定値は<languageKeyword>false</languageKeyword>です。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludeSystemApplicationHealthStatistics">
      <MemberSignature Language="C#" Value="public bool IncludeSystemApplicationHealthStatistics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IncludeSystemApplicationHealthStatistics" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealthStatisticsFilter.IncludeSystemApplicationHealthStatistics" />
      <MemberSignature Language="VB.NET" Value="Public Property IncludeSystemApplicationHealthStatistics As Boolean" />
      <MemberSignature Language="F#" Value="member this.IncludeSystemApplicationHealthStatistics : bool with get, set" Usage="System.Fabric.Health.ClusterHealthStatisticsFilter.IncludeSystemApplicationHealthStatistics" />
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
            取得または状態の統計がファブリックの情報を含めるかどうかを示すフラグを設定します。/システム アプリケーションです。
            </summary>
        <value>状態の統計がファブリックの情報を含めるかどうかを示すフラグ。/システム アプリケーションです。</value>
        <remarks>
          <para>
            IncludeSystemApplicationHealthStatistics に設定されている場合<languageKeyword>true</languageKeyword>、正常性の統計情報には、ファブリックに属しているエンティティが含まれます。/システム アプリケーションです。
            そうでない場合、クエリの結果には、ユーザー アプリケーションのみの正常性の統計情報が含まれます。
            既定値は<languageKeyword>false</languageKeyword>です。
            </para>
          <para>設定する必要があります ExcludeHealthStatistics IncludeSystemApplicationHealthStatistics を適用するために<languageKeyword>false</languageKeyword> (既定値)。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ClusterHealthStatisticsFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="clusterHealthStatisticsFilter.ToString " />
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
            フィルターの文字列表現を返します。
            </summary>
        <returns>フィルターの文字列形式。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>