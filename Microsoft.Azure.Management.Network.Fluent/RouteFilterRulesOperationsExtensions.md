<Type Name="RouteFilterRulesOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RouteFilterRulesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RouteFilterRulesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RouteFilterRulesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RouteFilterRulesOperationsExtensions = class" />
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
            RouteFilterRulesOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner routeFilterRuleParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner routeFilterRuleParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations * string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, routeFilterName, ruleName, routeFilterRuleParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="routeFilterRuleParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner" />
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
        <param name="ruleName">
            ルート フィルターの規則の名前。
            </param>
        <param name="routeFilterRuleParameters">
            作成または更新ルート フィルターの規則操作に渡されるパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成するか、指定したルート フィルター内のルートを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, routeFilterName, ruleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
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
        <param name="ruleName">
            ルールの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ルート フィルターから、指定されたルールを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; BeginUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner routeFilterRuleParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; BeginUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, class Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner routeFilterRuleParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations * string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, routeFilterName, ruleName, routeFilterRuleParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions/&lt;BeginUpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="routeFilterRuleParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner" />
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
        <param name="ruleName">
            ルート フィルターの規則の名前。
            </param>
        <param name="routeFilterRuleParameters">
            パラメーターは、更新プログラムのルート フィルターの規則の操作に指定します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したルート フィルター内のルートを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner routeFilterRuleParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner routeFilterRuleParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations * string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, routeFilterName, ruleName, routeFilterRuleParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="routeFilterRuleParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner" />
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
        <param name="ruleName">
            ルート フィルターの規則の名前。
            </param>
        <param name="routeFilterRuleParameters">
            作成または更新ルート フィルターの規則操作に渡されるパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成するか、指定したルート フィルター内のルートを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.DeleteAsync (operations, resourceGroupName, routeFilterName, ruleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions/&lt;DeleteAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
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
        <param name="ruleName">
            ルールの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ルート フィルターから、指定されたルールを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; GetAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; GetAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.GetAsync (operations, resourceGroupName, routeFilterName, ruleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
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
        <param name="ruleName">
            ルールの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ルート フィルターから、指定されたルールを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByRouteFilterAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;&gt; ListByRouteFilterAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;&gt; ListByRouteFilterAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.ListByRouteFilterAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByRouteFilterAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.ListByRouteFilterAsync (operations, resourceGroupName, routeFilterName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions/&lt;ListByRouteFilterAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations" RefType="this" />
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
            ルート フィルター内のすべての RouteFilterRules を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByRouteFilterNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;&gt; ListByRouteFilterNextAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;&gt; ListByRouteFilterNextAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.ListByRouteFilterNextAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByRouteFilterNextAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.ListByRouteFilterNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions/&lt;ListByRouteFilterNextAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations" RefType="this" />
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
            ルート フィルター内のすべての RouteFilterRules を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; UpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner routeFilterRuleParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; UpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, class Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner routeFilterRuleParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations * string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.UpdateAsync (operations, resourceGroupName, routeFilterName, ruleName, routeFilterRuleParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="routeFilterRuleParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner" />
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
        <param name="ruleName">
            ルート フィルターの規則の名前。
            </param>
        <param name="routeFilterRuleParameters">
            パラメーターは、更新プログラムのルート フィルターの規則の操作に指定します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したルート フィルター内のルートを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>