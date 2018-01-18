<Type Name="ClientDiscoveryForServiceSpecification" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForServiceSpecification">
  <TypeSignature Language="C#" Value="public class ClientDiscoveryForServiceSpecification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClientDiscoveryForServiceSpecification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForServiceSpecification" />
  <TypeSignature Language="VB.NET" Value="Public Class ClientDiscoveryForServiceSpecification" />
  <TypeSignature Language="F#" Value="type ClientDiscoveryForServiceSpecification = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6ab1e-101">Json のクライアントの探索で靴箱サービスの仕様を表すクラスです。</span><span class="sxs-lookup"><span data-stu-id="6ab1e-101">Class to represent shoebox service specification in json client discovery.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClientDiscoveryForServiceSpecification ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForServiceSpecification.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6ab1e-102">ClientDiscoveryForServiceSpecification クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6ab1e-102">Initializes a new instance of the ClientDiscoveryForServiceSpecification class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClientDiscoveryForServiceSpecification (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForLogSpecification&gt; logSpecifications = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForLogSpecification&gt; logSpecifications) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForServiceSpecification.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForLogSpecification})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional logSpecifications As IList(Of ClientDiscoveryForLogSpecification) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForServiceSpecification : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForLogSpecification&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForServiceSpecification" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForServiceSpecification logSpecifications" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="logSpecifications" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForLogSpecification&gt;" />
      </Parameters>
      <Docs>
        <param name="logSpecifications"><span data-ttu-id="6ab1e-103">この操作のログの仕様の一覧です。</span><span class="sxs-lookup"><span data-stu-id="6ab1e-103">List of log specifications of this operation.</span></span></param>
        <summary>
            <span data-ttu-id="6ab1e-104">ClientDiscoveryForServiceSpecification クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6ab1e-104">Initializes a new instance of the ClientDiscoveryForServiceSpecification class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogSpecifications">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForLogSpecification&gt; LogSpecifications { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForLogSpecification&gt; LogSpecifications" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForServiceSpecification.LogSpecifications" />
      <MemberSignature Language="VB.NET" Value="Public Property LogSpecifications As IList(Of ClientDiscoveryForLogSpecification)" />
      <MemberSignature Language="F#" Value="member this.LogSpecifications : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForLogSpecification&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForServiceSpecification.LogSpecifications" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="logSpecifications")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForLogSpecification&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ab1e-105">取得またはこの操作のログの仕様の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="6ab1e-105">Gets or sets list of log specifications of this operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>