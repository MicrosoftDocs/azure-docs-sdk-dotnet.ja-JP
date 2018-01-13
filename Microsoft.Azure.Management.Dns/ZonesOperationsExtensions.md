<Type Name="ZonesOperationsExtensions" FullName="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ZonesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ZonesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ZonesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ZonesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IZonesOperations, resourceGroupName As String, zoneName As String, Optional ifMatch As String = null)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Dns.IZonesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.BeginDelete (operations, resourceGroupName, zoneName, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
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
        <summary>
            DNS ゾーンを削除します。 警告: ゾーン内のすべての DNS レコードも削除されます。 削除操作は元に戻すことができません。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Dns.IZonesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, zoneName, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.ZonesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
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
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Dns.Models.Zone CreateOrUpdate (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, Microsoft.Azure.Management.Dns.Models.Zone parameters, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Dns.Models.Zone CreateOrUpdate(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, class Microsoft.Azure.Management.Dns.Models.Zone parameters, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.String,Microsoft.Azure.Management.Dns.Models.Zone,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IZonesOperations, resourceGroupName As String, zoneName As String, parameters As Zone, Optional ifMatch As String = null, Optional ifNoneMatch As String = null) As Zone" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Dns.IZonesOperations * string * string * Microsoft.Azure.Management.Dns.Models.Zone * string * string -&gt; Microsoft.Azure.Management.Dns.Models.Zone" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, zoneName, parameters, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Models.Zone</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Dns.Models.Zone" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
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
        <summary>
            作成するか、DNS ゾーンを更新します。 ゾーン内で DNS レコードを変更しません。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, Microsoft.Azure.Management.Dns.Models.Zone parameters, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Dns.Models.Zone&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, class Microsoft.Azure.Management.Dns.Models.Zone parameters, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.String,Microsoft.Azure.Management.Dns.Models.Zone,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Dns.IZonesOperations * string * string * Microsoft.Azure.Management.Dns.Models.Zone * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, zoneName, parameters, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.ZonesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Dns.Models.Zone" />
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
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.Delete(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IZonesOperations, resourceGroupName As String, zoneName As String, Optional ifMatch As String = null)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Dns.IZonesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.Delete (operations, resourceGroupName, zoneName, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
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
        <summary>
            DNS ゾーンを削除します。 警告: ゾーン内のすべての DNS レコードも削除されます。 削除操作は元に戻すことができません。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Dns.IZonesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.DeleteAsync (operations, resourceGroupName, zoneName, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.ZonesOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
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
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Dns.Models.Zone Get (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Dns.Models.Zone Get(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.Get(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IZonesOperations, resourceGroupName As String, zoneName As String) As Zone" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Dns.IZonesOperations * string * string -&gt; Microsoft.Azure.Management.Dns.Models.Zone" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.Get (operations, resourceGroupName, zoneName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Models.Zone</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
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
        <summary>
            DNS ゾーンを取得します。 ゾーンのプロパティが、ゾーン内でレコード セットではないを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt; GetAsync (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Dns.Models.Zone&gt; GetAsync(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Dns.IZonesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.GetAsync (operations, resourceGroupName, zoneName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.ZonesOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
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
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt; List (this Microsoft.Azure.Management.Dns.IZonesOperations operations, Nullable&lt;int&gt; top = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.Zone&gt; List(class Microsoft.Azure.Management.Dns.IZonesOperations operations, valuetype System.Nullable`1&lt;int32&gt; top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.List(Microsoft.Azure.Management.Dns.IZonesOperations,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IZonesOperations, Optional top As Nullable(Of Integer) = null) As IPage(Of Zone)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Dns.IZonesOperations * Nullable&lt;int&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.List (operations, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="top">
            返される DNS ゾーンの最大数。 指定されていない場合は、最大 100 個のゾーンを返します。
            </param>
        <summary>
            サブスクリプション内のすべてのリソース グループ内の DNS ゾーンを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt; ListAsync (this Microsoft.Azure.Management.Dns.IZonesOperations operations, Nullable&lt;int&gt; top = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt; ListAsync(class Microsoft.Azure.Management.Dns.IZonesOperations operations, valuetype System.Nullable`1&lt;int32&gt; top, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Dns.IZonesOperations,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Dns.IZonesOperations * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListAsync (operations, top, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.ZonesOperationsExtensions/&lt;ListAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
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
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt; ListByResourceGroup (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, Nullable&lt;int&gt; top = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.Zone&gt; ListByResourceGroup(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, valuetype System.Nullable`1&lt;int32&gt; top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IZonesOperations, resourceGroupName As String, Optional top As Nullable(Of Integer) = null) As IPage(Of Zone)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.Dns.IZonesOperations * string * Nullable&lt;int&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListByResourceGroup (operations, resourceGroupName, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
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
        <summary>
            リソース グループ内の DNS ゾーンを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, Nullable&lt;int&gt; top = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, valuetype System.Nullable`1&lt;int32&gt; top, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Dns.IZonesOperations * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, top, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.ZonesOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
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
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.Zone&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.Dns.IZonesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IZonesOperations, nextPageLink As String) As IPage(Of Zone)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.Dns.IZonesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <summary>
            リソース グループ内の DNS ゾーンを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.Dns.IZonesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.ZonesOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
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
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt; ListNext (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.Zone&gt; ListNext(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListNext(Microsoft.Azure.Management.Dns.IZonesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IZonesOperations, nextPageLink As String) As IPage(Of Zone)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Dns.IZonesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <summary>
            サブスクリプション内のすべてのリソース グループ内の DNS ゾーンを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Dns.IZonesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.ZonesOperationsExtensions/&lt;ListNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
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