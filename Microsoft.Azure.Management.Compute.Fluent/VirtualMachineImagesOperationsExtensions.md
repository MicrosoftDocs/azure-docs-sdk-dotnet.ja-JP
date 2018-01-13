<Type Name="VirtualMachineImagesOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineImagesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualMachineImagesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualMachineImagesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineImagesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualMachineImagesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualMachineImagesOperationsExtensions = class" />
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
            VirtualMachineImagesOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageInner&gt; GetAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations operations, string location, string publisherName, string offer, string skus, string version, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageInner&gt; GetAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations operations, string location, string publisherName, string offer, string skus, string version, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineImagesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineImagesOperationsExtensions.GetAsync (operations, location, publisherName, offer, skus, version, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineImagesOperationsExtensions/&lt;GetAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="publisherName" Type="System.String" />
        <Parameter Name="offer" Type="System.String" />
        <Parameter Name="skus" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="location">
            サポートされている Azure の地域の名前。
            </param>
        <param name="publisherName">
            有効なイメージがパブリッシャーです。
            </param>
        <param name="offer">
            有効なイメージが発行者の提供。
            </param>
        <param name="skus">
            有効なイメージの SKU。
            </param>
        <param name="version">
            有効なイメージの SKU バージョン。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            仮想マシンのイメージを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations operations, string location, string publisherName, string offer, string skus, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations operations, string location, string publisherName, string offer, string skus, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineImagesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations,System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations * string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineImagesOperationsExtensions.ListAsync (operations, location, publisherName, offer, skus, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineImagesOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="publisherName" Type="System.String" />
        <Parameter Name="offer" Type="System.String" />
        <Parameter Name="skus" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="location">
            サポートされている Azure の地域の名前。
            </param>
        <param name="publisherName">
            有効なイメージがパブリッシャーです。
            </param>
        <param name="offer">
            有効なイメージが発行者の提供。
            </param>
        <param name="skus">
            有効なイメージの SKU。
            </param>
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定した場所、パブリッシャー、プラン、および SKU のすべての仮想マシン イメージのバージョンの一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOffersAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt;&gt; ListOffersAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations operations, string location, string publisherName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt;&gt; ListOffersAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations operations, string location, string publisherName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineImagesOperationsExtensions.ListOffersAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListOffersAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineImagesOperationsExtensions.ListOffersAsync (operations, location, publisherName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineImagesOperationsExtensions/&lt;ListOffersAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="publisherName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="location">
            サポートされている Azure の地域の名前。
            </param>
        <param name="publisherName">
            有効なイメージがパブリッシャーです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            取得、指定した場所とパブリッシャーの仮想マシンのイメージの一覧を提供します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPublishersAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt;&gt; ListPublishersAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations operations, string location, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt;&gt; ListPublishersAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations operations, string location, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineImagesOperationsExtensions.ListPublishersAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListPublishersAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineImagesOperationsExtensions.ListPublishersAsync (operations, location, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineImagesOperationsExtensions/&lt;ListPublishersAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="location">
            サポートされている Azure の地域の名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された Azure の場所の仮想マシン イメージのパブリッシャーの一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSkusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt;&gt; ListSkusAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations operations, string location, string publisherName, string offer, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt;&gt; ListSkusAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations operations, string location, string publisherName, string offer, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineImagesOperationsExtensions.ListSkusAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListSkusAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineImagesOperationsExtensions.ListSkusAsync (operations, location, publisherName, offer, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineImagesOperationsExtensions/&lt;ListSkusAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="publisherName" Type="System.String" />
        <Parameter Name="offer" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="location">
            サポートされている Azure の地域の名前。
            </param>
        <param name="publisherName">
            有効なイメージがパブリッシャーです。
            </param>
        <param name="offer">
            有効なイメージが発行者の提供。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定した場所、パブリッシャー、およびプランの仮想マシンのイメージの Sku の一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>