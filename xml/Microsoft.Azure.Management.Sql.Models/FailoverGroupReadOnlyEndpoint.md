<Type Name="FailoverGroupReadOnlyEndpoint" FullName="Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint">
  <TypeSignature Language="C#" Value="public class FailoverGroupReadOnlyEndpoint" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FailoverGroupReadOnlyEndpoint extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint" />
  <TypeSignature Language="VB.NET" Value="Public Class FailoverGroupReadOnlyEndpoint" />
  <TypeSignature Language="F#" Value="type FailoverGroupReadOnlyEndpoint = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="05512-101">フェールオーバー グループ インスタンスのエンドポイントを読み取り専用です。</span><span class="sxs-lookup"><span data-stu-id="05512-101">Read-only endpoint of the failover group instance.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FailoverGroupReadOnlyEndpoint ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="05512-102">FailoverGroupReadOnlyEndpoint クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="05512-102">Initializes a new instance of the FailoverGroupReadOnlyEndpoint class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FailoverGroupReadOnlyEndpoint (string failoverPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string failoverPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional failoverPolicy As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint : string -&gt; Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint" Usage="new Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint failoverPolicy" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="failoverPolicy" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="failoverPolicy"><span data-ttu-id="05512-103">フェールオーバー グループの読み取り専用のエンドポイントのフェールオーバー ポリシー。</span><span class="sxs-lookup"><span data-stu-id="05512-103">Failover policy of the read-only endpoint for the failover group.</span></span> <span data-ttu-id="05512-104">使用可能な値が含まれます: '無効'、'Enabled'</span><span class="sxs-lookup"><span data-stu-id="05512-104">Possible values include: 'Disabled', 'Enabled'</span></span></param>
        <summary>
            <span data-ttu-id="05512-105">FailoverGroupReadOnlyEndpoint クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="05512-105">Initializes a new instance of the FailoverGroupReadOnlyEndpoint class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverPolicy">
      <MemberSignature Language="C#" Value="public string FailoverPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FailoverPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint.FailoverPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property FailoverPolicy As String" />
      <MemberSignature Language="F#" Value="member this.FailoverPolicy : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint.FailoverPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="failoverPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="05512-106">取得またはフェールオーバー グループの読み取り専用のエンドポイントのフェールオーバー ポリシーを設定します。</span><span class="sxs-lookup"><span data-stu-id="05512-106">Gets or sets failover policy of the read-only endpoint for the failover group.</span></span> <span data-ttu-id="05512-107">使用可能な値が含まれます: '無効'、'Enabled'</span><span class="sxs-lookup"><span data-stu-id="05512-107">Possible values include: 'Disabled', 'Enabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>