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
      <para>フィルターを表す<see cref="T:System.Fabric.Health.HealthStatistics" />です。</para>
    </summary>
    <remarks>使用できるフィルター<see cref="T:System.Fabric.Description.ServiceHealthQueryDescription" />正常性の統計情報の一部として返されるかどうかを指定する<see cref="T:System.Fabric.Health.ServiceHealth" />です。</remarks>
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
          <para><see cref="T:System.Fabric.Health.ServiceHealthStatisticsFilter" /> クラスの新しいインスタンスを初期化します。</para>
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
            取得または状態の統計をクエリの結果に含める必要があるかどうかを示すフラグを設定します。
            </summary>
        <value>状態の統計をクエリの結果に含める必要があるかどうかを示すフラグです。</value>
        <remarks>
          <para>
            ExcludeHealthStatistics に設定されている場合<languageKeyword>true</languageKeyword>状態の統計はクエリ結果の一部として返されません。
            それ以外の場合、クエリの結果には、パーティションの数に関する情報を含むサービスの正常性の統計が含まれています。 および、レプリカがで<see cref="F:System.Fabric.Health.HealthState.Ok" />、 <see cref="F:System.Fabric.Health.HealthState.Warning" />、および<see cref="F:System.Fabric.Health.HealthState.Error" />状態です。
            既定値は<languageKeyword>false</languageKeyword>です。
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
            フィルターの文字列表現を返します。
            </summary>
        <returns>フィルターの文字列形式。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>