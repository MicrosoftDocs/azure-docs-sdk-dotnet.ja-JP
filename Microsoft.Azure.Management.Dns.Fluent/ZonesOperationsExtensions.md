<Type Name="ZonesOperationsExtensions" FullName="Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ZonesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ZonesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ZonesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ZonesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ZonesOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Dns.Fluent.IZonesOperations operations, string resourceGroupName, string zoneName, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Dns.Fluent.IZonesOperations operations, string resourceGroupName, string zoneName, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Dns.Fluent.IZonesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Dns.Fluent.IZonesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, zoneName, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="zoneName">
            (末尾のドット) なしの DNS ゾーンの名前。
            </param>
        <param name="ifMatch">
            DNS ゾーンの etag です。 常に現在のゾーンを削除するには、この値を省略します。 誤って削除したり、同時変更を防ぐために最後に、発生の etag 値を指定します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            DNS ゾーンを削除します。 警告: ゾーン内のすべての DNS レコードも削除されます。 削除操作は元に戻すことができません。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Dns.Fluent.IZonesOperations operations, string resourceGroupName, string zoneName, Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner parameters, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Dns.Fluent.IZonesOperations operations, string resourceGroupName, string zoneName, class Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner parameters, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Dns.Fluent.IZonesOperations,System.String,System.String,Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Dns.Fluent.IZonesOperations * string * string * Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, zoneName, parameters, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="zoneName">
            (末尾のドット) なしの DNS ゾーンの名前。
            </param>
        <param name="parameters">
            CreateOrUpdate 操作に渡されるパラメーター。
            </param>
        <param name="ifMatch">
            DNS ゾーンの etag です。 常に現在のゾーンを上書きするには、この値を省略します。 変更できないように誤って overwritting 同時実行を最後に、発生の etag 値を指定します。
            </param>
        <param name="ifNoneMatch">
            設定 ' *' 新しい DNS ゾーンを作成するが、既存のゾーンの更新を防ぐために使用できるようにします。 その他の値は無視されます。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成するか、DNS ゾーンを更新します。 ゾーン内で DNS レコードを変更しません。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner&gt; DeleteAsync (this Microsoft.Azure.Management.Dns.Fluent.IZonesOperations operations, string resourceGroupName, string zoneName, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner&gt; DeleteAsync(class Microsoft.Azure.Management.Dns.Fluent.IZonesOperations operations, string resourceGroupName, string zoneName, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Dns.Fluent.IZonesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Dns.Fluent.IZonesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions.DeleteAsync (operations, resourceGroupName, zoneName, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="zoneName">
            (末尾のドット) なしの DNS ゾーンの名前。
            </param>
        <param name="ifMatch">
            DNS ゾーンの etag です。 常に現在のゾーンを削除するには、この値を省略します。 誤って削除したり、同時変更を防ぐために最後に、発生の etag 値を指定します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            DNS ゾーンを削除します。 警告: ゾーン内のすべての DNS レコードも削除されます。 削除操作は元に戻すことができません。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt; GetAsync (this Microsoft.Azure.Management.Dns.Fluent.IZonesOperations operations, string resourceGroupName, string zoneName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt; GetAsync(class Microsoft.Azure.Management.Dns.Fluent.IZonesOperations operations, string resourceGroupName, string zoneName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Dns.Fluent.IZonesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Dns.Fluent.IZonesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions.GetAsync (operations, resourceGroupName, zoneName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions/&lt;GetAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="zoneName">
            (末尾のドット) なしの DNS ゾーンの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            DNS ゾーンを取得します。 ゾーンのプロパティが、ゾーン内でレコード セットではないを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Dns.Fluent.IZonesOperations operations, Nullable&lt;int&gt; top = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Dns.Fluent.IZonesOperations operations, valuetype System.Nullable`1&lt;int32&gt; top, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Dns.Fluent.IZonesOperations,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Dns.Fluent.IZonesOperations * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions.ListAsync (operations, top, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions/&lt;ListAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IZonesOperations" RefType="this" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="top">
            返される DNS ゾーンの最大数。 指定されていない場合は、最大 100 個のゾーンを返します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            サブスクリプション内のすべてのリソース グループ内の DNS ゾーンを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Dns.Fluent.IZonesOperations operations, string resourceGroupName, Nullable&lt;int&gt; top = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Dns.Fluent.IZonesOperations operations, string resourceGroupName, valuetype System.Nullable`1&lt;int32&gt; top, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Dns.Fluent.IZonesOperations,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Dns.Fluent.IZonesOperations * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, top, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="top">
            返されるレコードの最大数を設定します。 指定されていない場合は、最大 100 のレコード セットを返します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソース グループ内の DNS ゾーンを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.Dns.Fluent.IZonesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.Dns.Fluent.IZonesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.Dns.Fluent.IZonesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.Dns.Fluent.IZonesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IZonesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソース グループ内の DNS ゾーンを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Dns.Fluent.IZonesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Dns.Fluent.IZonesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Dns.Fluent.IZonesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Dns.Fluent.IZonesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions/&lt;ListNextAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IZonesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            サブスクリプション内のすべてのリソース グループ内の DNS ゾーンを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>