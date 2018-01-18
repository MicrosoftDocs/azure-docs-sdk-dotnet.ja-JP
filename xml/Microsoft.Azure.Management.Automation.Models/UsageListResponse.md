<Type Name="UsageListResponse" FullName="Microsoft.Azure.Management.Automation.Models.UsageListResponse">
  <TypeSignature Language="C#" Value="public class UsageListResponse : Microsoft.Azure.AzureOperationResponse, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Automation.Models.Usage&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UsageListResponse extends Microsoft.Azure.AzureOperationResponse implements class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Automation.Models.Usage&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.Models.UsageListResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class UsageListResponse&#xA;Inherits AzureOperationResponse&#xA;Implements IEnumerable(Of Usage)" />
  <TypeSignature Language="F#" Value="type UsageListResponse = class&#xA;    inherit AzureOperationResponse&#xA;    interface seq&lt;Usage&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.AzureOperationResponse</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Automation.Models.Usage&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="142f4-101">使用状況の取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="142f4-101">The response model for the get usage operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UsageListResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.UsageListResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="142f4-102">UsageListResponse クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="142f4-102">Initializes a new instance of the UsageListResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;Microsoft.Azure.Management.Automation.Models.Usage&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;class Microsoft.Azure.Management.Automation.Models.Usage&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.UsageListResponse.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of Usage)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;Microsoft.Azure.Management.Automation.Models.Usage&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;Microsoft.Azure.Management.Automation.Models.Usage&gt;" Usage="usageListResponse.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;Microsoft.Azure.Management.Automation.Models.Usage&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="142f4-103">使用状況のシーケンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="142f4-103">Gets the sequence of Usage.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.UsageListResponse.System#Collections#IEnumerable#GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Function GetEnumerator () As IEnumerator Implements IEnumerable.GetEnumerator" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.IEnumerable.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.IEnumerator</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="142f4-104">使用状況のシーケンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="142f4-104">Gets the sequence of Usage.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Usage">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Automation.Models.Usage&gt; Usage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Automation.Models.Usage&gt; Usage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.UsageListResponse.Usage" />
      <MemberSignature Language="VB.NET" Value="Public Property Usage As IList(Of Usage)" />
      <MemberSignature Language="F#" Value="member this.Usage : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Automation.Models.Usage&gt; with get, set" Usage="Microsoft.Azure.Management.Automation.Models.UsageListResponse.Usage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Automation.Models.Usage&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="142f4-105">省略可能。</span><span class="sxs-lookup"><span data-stu-id="142f4-105">Optional.</span></span> <span data-ttu-id="142f4-106">取得または使用率を設定します。</span><span class="sxs-lookup"><span data-stu-id="142f4-106">Gets or sets usage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>