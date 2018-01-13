<Type Name="ServicePlacementRequireDomainDistributionPolicyDescription" FullName="System.Fabric.Description.ServicePlacementRequireDomainDistributionPolicyDescription">
  <TypeSignature Language="C#" Value="public sealed class ServicePlacementRequireDomainDistributionPolicyDescription : System.Fabric.Description.ServicePlacementPolicyDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServicePlacementRequireDomainDistributionPolicyDescription extends System.Fabric.Description.ServicePlacementPolicyDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServicePlacementRequireDomainDistributionPolicyDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServicePlacementRequireDomainDistributionPolicyDescription&#xA;Inherits ServicePlacementPolicyDescription" />
  <TypeSignature Language="F#" Value="type ServicePlacementRequireDomainDistributionPolicyDescription = class&#xA;    inherit ServicePlacementPolicyDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.ServicePlacementPolicyDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>同じパーティションからの 2 つのレプリカが同じ障害やアップグレード ドメインに配置しないでくださいを示す配置ポリシーを指定します。  
            これは一般的ではありませんは、計画外の停止による同時実行の失敗または後続/同時発生したエラーのそれ以外の場合のリスクが増大するサービスに公開できます。 たとえば、場所ごとの 1 つのレプリカとの別のデータ センター間でのレプリカが展開されている場合を考えます。 データ センターのいずれかがオフラインになったことは通常、データ センターに配置されたレプリカは、残りのデータ センターのいずれかにパックされます。 これが望ましくない場合は、このポリシーを設定してください。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePlacementRequireDomainDistributionPolicyDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServicePlacementRequireDomainDistributionPolicyDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Description.ServicePlacementRequireDomainDistributionPolicyDescription" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServicePlacementRequireDomainDistributionPolicyDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="servicePlacementRequireDomainDistributionPolicyDescription.ToString " />
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
          <para> 
            'RequiredDomainDistribution、DomainName' 形式の RequiredDomainDistribution サービス配置ポリシーの文字列表現を返す 
            </para>
        </summary>
        <returns>
          <para>オブジェクトを表す文字列。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>