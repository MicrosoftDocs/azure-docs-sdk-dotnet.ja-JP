<Type Name="DeployedApplicationHealthState" FullName="System.Fabric.Health.DeployedApplicationHealthState">
  <TypeSignature Language="C#" Value="public sealed class DeployedApplicationHealthState : System.Fabric.Health.EntityHealthState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedApplicationHealthState extends System.Fabric.Health.EntityHealthState" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeployedApplicationHealthState" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedApplicationHealthState&#xA;Inherits EntityHealthState" />
  <TypeSignature Language="F#" Value="type DeployedApplicationHealthState = class&#xA;    inherit EntityHealthState" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.EntityHealthState</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="5a7e7-101">エンティティの識別子を含む配置のアプリケーションの正常性状態と、集計された正常性状態を表します。</span><span class="sxs-lookup"><span data-stu-id="5a7e7-101">Represents the health state of a deployed application, which contains the entity identifier and the aggregated health state.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealthState.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Health.DeployedApplicationHealthState.ApplicationName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="5a7e7-102">アプリケーションの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="5a7e7-102">Gets the application name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="5a7e7-103"><see cref="T:System.Uri" />アプリケーションです。</span><span class="sxs-lookup"><span data-stu-id="5a7e7-103">The <see cref="T:System.Uri" /> of the application.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealthState.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Health.DeployedApplicationHealthState.NodeName" />
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
          <para><span data-ttu-id="5a7e7-104">展開済みアプリケーションのノード名を取得します。</span><span class="sxs-lookup"><span data-stu-id="5a7e7-104">Gets the node name of the deployed application.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="5a7e7-105"><see cref="T:System.String" />ノード名を表すです。</span><span class="sxs-lookup"><span data-stu-id="5a7e7-105">The <see cref="T:System.String" /> representing the node name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedApplicationHealthState.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="deployedApplicationHealthState.ToString " />
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
            <span data-ttu-id="5a7e7-106">Id と、正常性状態を含むノードで、アプリケーションの文字列説明を作成します。</span><span class="sxs-lookup"><span data-stu-id="5a7e7-106">Creates a string description of the application on the node, containing the id and the health state.</span></span>
            </summary>
        <returns><span data-ttu-id="5a7e7-107">説明の文字列、<see cref="T:System.Fabric.Health.DeployedApplicationHealthState" />です。</span><span class="sxs-lookup"><span data-stu-id="5a7e7-107">String description of the <see cref="T:System.Fabric.Health.DeployedApplicationHealthState" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>