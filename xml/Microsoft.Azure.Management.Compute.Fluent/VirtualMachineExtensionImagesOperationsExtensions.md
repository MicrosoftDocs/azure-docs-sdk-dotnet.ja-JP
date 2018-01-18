<Type Name="VirtualMachineExtensionImagesOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtensionImagesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualMachineExtensionImagesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualMachineExtensionImagesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtensionImagesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualMachineExtensionImagesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualMachineExtensionImagesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="92737-101">VirtualMachineExtensionImagesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="92737-101">Extension methods for VirtualMachineExtensionImagesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionImageInner&gt; GetAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImagesOperations operations, string location, string publisherName, string type, string version, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionImageInner&gt; GetAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImagesOperations operations, string location, string publisherName, string type, string version, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtensionImagesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImagesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImagesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionImageInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtensionImagesOperationsExtensions.GetAsync (operations, location, publisherName, type, version, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtensionImagesOperationsExtensions/&lt;GetAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionImageInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="publisherName" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="92737-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="92737-102">The operations group for this extension method.</span></span>
            </param>
        <param name="location"></param>
        <param name="publisherName"></param>
        <param name="type"></param>
        <param name="version"></param>
        <param name="cancellationToken">
            <span data-ttu-id="92737-103">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="92737-103">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="92737-104">仮想マシン拡張機能のイメージを取得します。</span><span class="sxs-lookup"><span data-stu-id="92737-104">Gets a virtual machine extension image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTypesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionImageInner&gt;&gt; ListTypesAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImagesOperations operations, string location, string publisherName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionImageInner&gt;&gt; ListTypesAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImagesOperations operations, string location, string publisherName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtensionImagesOperationsExtensions.ListTypesAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImagesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTypesAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImagesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionImageInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtensionImagesOperationsExtensions.ListTypesAsync (operations, location, publisherName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtensionImagesOperationsExtensions/&lt;ListTypesAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionImageInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="publisherName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="92737-105">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="92737-105">The operations group for this extension method.</span></span>
            </param>
        <param name="location"></param>
        <param name="publisherName"></param>
        <param name="cancellationToken">
            <span data-ttu-id="92737-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="92737-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="92737-107">仮想マシン拡張機能のイメージの種類の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="92737-107">Gets a list of virtual machine extension image types.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVersionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionImageInner&gt;&gt; ListVersionsAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImagesOperations operations, string location, string publisherName, string type, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionImageInner&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionImageInner&gt;&gt; ListVersionsAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImagesOperations operations, string location, string publisherName, string type, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionImageInner&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtensionImagesOperationsExtensions.ListVersionsAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImagesOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionImageInner},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListVersionsAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImagesOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionImageInner&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionImageInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtensionImagesOperationsExtensions.ListVersionsAsync (operations, location, publisherName, type, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtensionImagesOperationsExtensions/&lt;ListVersionsAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionImageInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="publisherName" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionImageInner&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="92737-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="92737-108">The operations group for this extension method.</span></span>
            </param>
        <param name="location"></param>
        <param name="publisherName"></param>
        <param name="type"></param>
        <param name="odataQuery">
            <span data-ttu-id="92737-109">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="92737-109">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="92737-110">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="92737-110">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="92737-111">仮想マシン拡張機能のイメージのバージョンの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="92737-111">Gets a list of virtual machine extension image versions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>