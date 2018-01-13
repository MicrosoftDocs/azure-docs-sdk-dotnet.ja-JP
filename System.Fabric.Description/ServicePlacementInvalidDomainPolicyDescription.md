<Type Name="ServicePlacementInvalidDomainPolicyDescription" FullName="System.Fabric.Description.ServicePlacementInvalidDomainPolicyDescription">
  <TypeSignature Language="C#" Value="public sealed class ServicePlacementInvalidDomainPolicyDescription : System.Fabric.Description.ServicePlacementPolicyDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServicePlacementInvalidDomainPolicyDescription extends System.Fabric.Description.ServicePlacementPolicyDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServicePlacementInvalidDomainPolicyDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServicePlacementInvalidDomainPolicyDescription&#xA;Inherits ServicePlacementPolicyDescription" />
  <TypeSignature Language="F#" Value="type ServicePlacementInvalidDomainPolicyDescription = class&#xA;    inherit ServicePlacementPolicyDescription" />
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
      <para>特定の障害やアップグレード ドメインが必要があります、インスタンスの配置またはにこのポリシーが適用されるサービスのレプリカ用に使用しないことを示すポリシーを表します。</para>
    </summary>
    <remarks>
      <para>たとえば、地理的に分散リングであるあります可能性があります政治的または法的要件により、特定の地域で実行する必要はありませんが。 ここではそのドメインは、このポリシーを無効として定義できます。 </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePlacementInvalidDomainPolicyDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServicePlacementInvalidDomainPolicyDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Description.ServicePlacementInvalidDomainPolicyDescription" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DomainName">
      <MemberSignature Language="C#" Value="public string DomainName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DomainName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServicePlacementInvalidDomainPolicyDescription.DomainName" />
      <MemberSignature Language="VB.NET" Value="Public Property DomainName As String" />
      <MemberSignature Language="F#" Value="member this.DomainName : string with get, set" Usage="System.Fabric.Description.ServicePlacementInvalidDomainPolicyDescription.DomainName" />
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
          <para>取得またはそれが無効であるは、このサービスを配置する、文字列として、フォールト ドメインの名前を設定します。</para>
        </summary>
        <value>
          <para>文字列、それが無効であるは、このサービスを配置すると、フォールト ドメインの名前。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServicePlacementInvalidDomainPolicyDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="servicePlacementInvalidDomainPolicyDescription.ToString " />
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
            'InvalidDomain、DomainName' 形式の InvalidDomain サービス配置ポリシーの文字列表現を返す 
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