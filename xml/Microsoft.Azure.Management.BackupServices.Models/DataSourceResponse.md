<Type Name="DataSourceResponse" FullName="Microsoft.Azure.Management.BackupServices.Models.DataSourceResponse">
  <TypeSignature Language="C#" Value="public class DataSourceResponse : Microsoft.Azure.Management.BackupServices.Models.ManagementBaseObject, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.BackupServices.Models.DataSourceInfo&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataSourceResponse extends Microsoft.Azure.Management.BackupServices.Models.ManagementBaseObject implements class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.BackupServices.Models.DataSourceInfo&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.Models.DataSourceResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class DataSourceResponse&#xA;Inherits ManagementBaseObject&#xA;Implements IEnumerable(Of DataSourceInfo)" />
  <TypeSignature Language="F#" Value="type DataSourceResponse = class&#xA;    inherit ManagementBaseObject&#xA;    interface seq&lt;DataSourceInfo&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.BackupServices.Models.ManagementBaseObject</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.BackupServices.Models.DataSourceInfo&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="3317c-101">管理一覧の応答の定義。</span><span class="sxs-lookup"><span data-stu-id="3317c-101">The definition of a Management List Response.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataSourceResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.Models.DataSourceResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3317c-102">DataSourceResponse クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3317c-102">Initializes a new instance of the DataSourceResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;Microsoft.Azure.Management.BackupServices.Models.DataSourceInfo&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;class Microsoft.Azure.Management.BackupServices.Models.DataSourceInfo&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.Models.DataSourceResponse.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of DataSourceInfo)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;Microsoft.Azure.Management.BackupServices.Models.DataSourceInfo&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;Microsoft.Azure.Management.BackupServices.Models.DataSourceInfo&gt;" Usage="dataSourceResponse.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;Microsoft.Azure.Management.BackupServices.Models.DataSourceInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3317c-103">オブジェクトのシーケンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="3317c-103">Gets the sequence of Objects.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Objects">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BackupServices.Models.DataSourceInfo&gt; Objects { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BackupServices.Models.DataSourceInfo&gt; Objects" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.Models.DataSourceResponse.Objects" />
      <MemberSignature Language="VB.NET" Value="Public Property Objects As IList(Of DataSourceInfo)" />
      <MemberSignature Language="F#" Value="member this.Objects : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BackupServices.Models.DataSourceInfo&gt; with get, set" Usage="Microsoft.Azure.Management.BackupServices.Models.DataSourceResponse.Objects" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BackupServices.Models.DataSourceInfo&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3317c-104">省略可能。</span><span class="sxs-lookup"><span data-stu-id="3317c-104">Optional.</span></span> <span data-ttu-id="3317c-105">ソース サーバーの ID。</span><span class="sxs-lookup"><span data-stu-id="3317c-105">The ID of the source Server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResultCount">
      <MemberSignature Language="C#" Value="public int ResultCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ResultCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.Models.DataSourceResponse.ResultCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ResultCount As Integer" />
      <MemberSignature Language="F#" Value="member this.ResultCount : int with get, set" Usage="Microsoft.Azure.Management.BackupServices.Models.DataSourceResponse.ResultCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3317c-106">省略可能。</span><span class="sxs-lookup"><span data-stu-id="3317c-106">Optional.</span></span> <span data-ttu-id="3317c-107">ソース サーバーの ID。</span><span class="sxs-lookup"><span data-stu-id="3317c-107">The ID of the source Server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Skiptoken">
      <MemberSignature Language="C#" Value="public string Skiptoken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Skiptoken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.Models.DataSourceResponse.Skiptoken" />
      <MemberSignature Language="VB.NET" Value="Public Property Skiptoken As String" />
      <MemberSignature Language="F#" Value="member this.Skiptoken : string with get, set" Usage="Microsoft.Azure.Management.BackupServices.Models.DataSourceResponse.Skiptoken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3317c-108">省略可能。</span><span class="sxs-lookup"><span data-stu-id="3317c-108">Optional.</span></span> <span data-ttu-id="3317c-109">ソース サーバーの ID。</span><span class="sxs-lookup"><span data-stu-id="3317c-109">The ID of the source Server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.Models.DataSourceResponse.System#Collections#IEnumerable#GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Function GetEnumerator () As IEnumerator Implements IEnumerable.GetEnumerator" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.IEnumerable.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.IEnumerator</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3317c-110">オブジェクトのシーケンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="3317c-110">Gets the sequence of Objects.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>