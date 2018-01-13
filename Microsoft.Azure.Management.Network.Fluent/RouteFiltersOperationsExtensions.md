<Type Name="RouteFiltersOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RouteFiltersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RouteFiltersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RouteFiltersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RouteFiltersOperationsExtensions = class" />
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
            RouteFiltersOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner routeFilterParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner routeFilterParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, routeFilterName, routeFilterParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="routeFilterParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="routeFilterName">
            ルート フィルターの名前。
            </param>
        <param name="routeFilterParameters">
            作成または更新のルート フィルター操作に渡されるパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成するか、指定されたリソース グループ内のルート フィルターを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, routeFilterName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions/&lt;BeginDeleteAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="routeFilterName">
            ルート フィルターの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したルート フィルターを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt; BeginUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner routeFilterParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt; BeginUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, class Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner routeFilterParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, routeFilterName, routeFilterParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions/&lt;BeginUpdateAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="routeFilterParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="routeFilterName">
            ルート フィルターの名前。
            </param>
        <param name="routeFilterParameters">
            パラメーターは、更新プログラムのルート フィルターの操作に指定します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたリソース グループ内のルート フィルターを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner routeFilterParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner routeFilterParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, routeFilterName, routeFilterParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="routeFilterParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="routeFilterName">
            ルート フィルターの名前。
            </param>
        <param name="routeFilterParameters">
            作成または更新のルート フィルター操作に渡されるパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成するか、指定されたリソース グループ内のルート フィルターを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.DeleteAsync (operations, resourceGroupName, routeFilterName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions/&lt;DeleteAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="routeFilterName">
            ルート フィルターの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したルート フィルターを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt; GetAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt; GetAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.GetAsync (operations, resourceGroupName, routeFilterName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="routeFilterName">
            ルート フィルターの名前。
            </param>
        <param name="expand">
            参照先の express route bgp ピアリング リソースを展開します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したルート フィルターを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions/&lt;ListAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            サブスクリプションのすべてのルート フィルターを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソース グループ内のすべてのルート フィルターを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations" RefType="this" />
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
            リソース グループ内のすべてのルート フィルターを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions/&lt;ListNextAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations" RefType="this" />
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
            サブスクリプションのすべてのルート フィルターを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt; UpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner routeFilterParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt; UpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, class Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner routeFilterParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.UpdateAsync (operations, resourceGroupName, routeFilterName, routeFilterParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="routeFilterParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="routeFilterName">
            ルート フィルターの名前。
            </param>
        <param name="routeFilterParameters">
            パラメーターは、更新プログラムのルート フィルターの操作に指定します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたリソース グループ内のルート フィルターを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>