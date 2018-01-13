<Type Name="ServicePlacementPreferPrimaryDomainPolicyDescription" FullName="System.Fabric.Description.ServicePlacementPreferPrimaryDomainPolicyDescription">
  <TypeSignature Language="C#" Value="public sealed class ServicePlacementPreferPrimaryDomainPolicyDescription : System.Fabric.Description.ServicePlacementPolicyDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServicePlacementPreferPrimaryDomainPolicyDescription extends System.Fabric.Description.ServicePlacementPolicyDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServicePlacementPreferPrimaryDomainPolicyDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServicePlacementPreferPrimaryDomainPolicyDescription&#xA;Inherits ServicePlacementPolicyDescription" />
  <TypeSignature Language="F#" Value="type ServicePlacementPreferPrimaryDomainPolicyDescription = class&#xA;    inherit ServicePlacementPolicyDescription" />
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
      <para>表す、<see cref="T:System.Fabric.Description.ServicePlacementPolicyDescription" />サービスのプライマリ レプリカが最適に配置すること、特定のドメインを示します。</para>
    </summary>
    <remarks>
      <para>この制約は通常、Service Fabric クラスターが特定のフォールト ドメインの地理的に分散シナリオで、サービスのプライマリ レプリカを配置することを指定するために地理的に配布されているシナリオでのフォールト ドメインと使用します。通常、地域またはデータ センターの境界に配置します。 最適化のためであること、プライマリ レプリカなる可能性がありますいない障害、容量の制限、またはその他の制約のためには、このドメイン内にあることに注意してください。</para>
    </remarks>
    <example>
      <code>
            サービス配置ポリシー ServicePlacementPreferPrimaryDomainPolicyDescription placementPolicy を作成する新しい ServicePlacementPreferPrimaryDomainPolicyDescription(); を =placementPolicy.DomainName =@"fd:\Datacenter1"です。
            
            ステートフル サービスの説明 StatefulServiceDescription ssd に追加する新しい StatefulServiceDescription(); を =ssd。PlacementPolicies.Add(placementPolicy) です。</code>
    </example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePlacementPreferPrimaryDomainPolicyDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServicePlacementPreferPrimaryDomainPolicyDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>新しいインスタンスを初期化して、<see cref="T:System.Fabric.Description.ServicePlacementPreferPrimaryDomainPolicyDescription" />クラスです。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DomainName">
      <MemberSignature Language="C#" Value="public string DomainName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DomainName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServicePlacementPreferPrimaryDomainPolicyDescription.DomainName" />
      <MemberSignature Language="VB.NET" Value="Public Property DomainName As String" />
      <MemberSignature Language="F#" Value="member this.DomainName : string with get, set" Usage="System.Fabric.Description.ServicePlacementPreferPrimaryDomainPolicyDescription.DomainName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または優先的に配置する必要があります、プライマリ レプリカ ドメインの文字列名を設定します。</para>
        </summary>
        <value>
          <para>優先的に配置する必要があります、プライマリ レプリカのドメインの文字列名。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServicePlacementPreferPrimaryDomainPolicyDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="servicePlacementPreferPrimaryDomainPolicyDescription.ToString " />
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
            'PreferPrimaryDomain、DomainName' 形式の PreferPrimaryDomain サービス配置ポリシーの文字列表現を返す 
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