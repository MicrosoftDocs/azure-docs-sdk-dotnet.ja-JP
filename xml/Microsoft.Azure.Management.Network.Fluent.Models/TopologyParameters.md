<Type Name="TopologyParameters" FullName="Microsoft.Azure.Management.Network.Fluent.Models.TopologyParameters">
  <TypeSignature Language="C#" Value="public class TopologyParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TopologyParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.TopologyParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class TopologyParameters" />
  <TypeSignature Language="F#" Value="type TopologyParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fe05a-101">トポロジの表現を定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="fe05a-101">Parameters that define the representation of topology.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TopologyParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.TopologyParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fe05a-102">TopologyParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fe05a-102">Initializes a new instance of the TopologyParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TopologyParameters (string targetResourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string targetResourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.TopologyParameters.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (targetResourceGroupName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.TopologyParameters : string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.TopologyParameters" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.TopologyParameters targetResourceGroupName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="targetResourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="targetResourceGroupName"><span data-ttu-id="fe05a-103">トポロジを実行するターゲット リソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="fe05a-103">The name of the target resource group to perform topology on.</span></span></param>
        <summary>
            <span data-ttu-id="fe05a-104">TopologyParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fe05a-104">Initializes a new instance of the TopologyParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetResourceGroupName">
      <MemberSignature Language="C#" Value="public string TargetResourceGroupName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetResourceGroupName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.TopologyParameters.TargetResourceGroupName" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetResourceGroupName As String" />
      <MemberSignature Language="F#" Value="member this.TargetResourceGroupName : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.TopologyParameters.TargetResourceGroupName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetResourceGroupName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fe05a-105">取得またはのトポロジを実行するターゲット リソース グループの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="fe05a-105">Gets or sets the name of the target resource group to perform topology on.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.TopologyParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="topologyParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fe05a-106">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="fe05a-106">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fe05a-107">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fe05a-107">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>