<Type Name="EndpointsOperationsExtensions" FullName="Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class EndpointsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit EndpointsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module EndpointsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type EndpointsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            EndpointsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt; BeginCreateAsync (this Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner endpoint, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt; BeginCreateAsync(class Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, class Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner endpoint, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations * string * string * string * Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, profileName, endpointName, endpoint, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions/&lt;BeginCreateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="endpoint" Type="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="profileName">
            リソース グループ内で一意である CDN プロファイルの名前です。
            </param>
        <param name="endpointName">
            グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。
            </param>
        <param name="endpoint">
            エンドポイントのプロパティ
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したエンドポイント名、型指定されたサブスクリプション、リソース グループとプロファイルを新しい CDN エンドポイントを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, profileName, endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="profileName">
            リソース グループ内で一意である CDN プロファイルの名前です。
            </param>
        <param name="endpointName">
            グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したエンドポイント名、型指定されたサブスクリプション、リソース グループとプロファイルの既存の CDN エンドポイントを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginLoadContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginLoadContentAsync (this Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, System.Collections.Generic.IList&lt;string&gt; contentPaths, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginLoadContentAsync(class Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, class System.Collections.Generic.IList`1&lt;string&gt; contentPaths, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.BeginLoadContentAsync(Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations,System.String,System.String,System.String,System.Collections.Generic.IList{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginLoadContentAsync : Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations * string * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.BeginLoadContentAsync (operations, resourceGroupName, profileName, endpointName, contentPaths, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions/&lt;BeginLoadContentAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="contentPaths" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="profileName">
            リソース グループ内で一意である CDN プロファイルの名前です。
            </param>
        <param name="endpointName">
            グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。
            </param>
        <param name="contentPaths">
            読み込まれるコンテンツへのパス。 パスは、元のファイルの相対 URL を指定します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            CDN のコンテンツを事前に読み込みます。 Verizon プロファイルで使用できます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPurgeContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginPurgeContentAsync (this Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, System.Collections.Generic.IList&lt;string&gt; contentPaths, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginPurgeContentAsync(class Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, class System.Collections.Generic.IList`1&lt;string&gt; contentPaths, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.BeginPurgeContentAsync(Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations,System.String,System.String,System.String,System.Collections.Generic.IList{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginPurgeContentAsync : Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations * string * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.BeginPurgeContentAsync (operations, resourceGroupName, profileName, endpointName, contentPaths, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions/&lt;BeginPurgeContentAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="contentPaths" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="profileName">
            リソース グループ内で一意である CDN プロファイルの名前です。
            </param>
        <param name="endpointName">
            グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。
            </param>
        <param name="contentPaths">
            消去するコンテンツへのパス。 ファイル パスまたはワイルド カード ディレクトリを記述できます。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            CDN からコンテンツを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt; BeginStartAsync (this Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt; BeginStartAsync(class Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.BeginStartAsync(Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginStartAsync : Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.BeginStartAsync (operations, resourceGroupName, profileName, endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions/&lt;BeginStartAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="profileName">
            リソース グループ内で一意である CDN プロファイルの名前です。
            </param>
        <param name="endpointName">
            グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            停止状態にある既存の CDN エンドポイントを開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt; BeginStopAsync (this Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt; BeginStopAsync(class Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.BeginStopAsync(Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginStopAsync : Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.BeginStopAsync (operations, resourceGroupName, profileName, endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions/&lt;BeginStopAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="profileName">
            リソース グループ内で一意である CDN プロファイルの名前です。
            </param>
        <param name="endpointName">
            グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            既存の実行中の CDN エンドポイントを停止します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt; BeginUpdateAsync (this Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner endpointUpdateProperties, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt; BeginUpdateAsync(class Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, class Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner endpointUpdateProperties, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations * string * string * string * Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, profileName, endpointName, endpointUpdateProperties, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions/&lt;BeginUpdateAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="endpointUpdateProperties" Type="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="profileName">
            リソース グループ内で一意である CDN プロファイルの名前です。
            </param>
        <param name="endpointName">
            グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。
            </param>
        <param name="endpointUpdateProperties">
            エンドポイントの更新のプロパティ
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したエンドポイント名、型指定されたサブスクリプション、リソース グループとプロファイルでは、既存の CDN エンドポイントを更新します。 エンドポイントの作成後は、タグと配信元ホスト ヘッダーのみを更新できます。 元のドメインを更新するには、Origin の更新操作を使用します。 カスタム ドメインを更新するには、カスタム ドメインの更新操作を使用します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt; CreateAsync (this Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner endpoint, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt; CreateAsync(class Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, class Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner endpoint, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations * string * string * string * Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.CreateAsync (operations, resourceGroupName, profileName, endpointName, endpoint, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions/&lt;CreateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="endpoint" Type="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="profileName">
            リソース グループ内で一意である CDN プロファイルの名前です。
            </param>
        <param name="endpointName">
            グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。
            </param>
        <param name="endpoint">
            エンドポイントのプロパティ
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したエンドポイント名、型指定されたサブスクリプション、リソース グループとプロファイルを新しい CDN エンドポイントを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.DeleteAsync (operations, resourceGroupName, profileName, endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions/&lt;DeleteAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="profileName">
            リソース グループ内で一意である CDN プロファイルの名前です。
            </param>
        <param name="endpointName">
            グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したエンドポイント名、型指定されたサブスクリプション、リソース グループとプロファイルの既存の CDN エンドポイントを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt; GetAsync (this Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt; GetAsync(class Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.GetAsync (operations, resourceGroupName, profileName, endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="profileName">
            リソース グループ内で一意である CDN プロファイルの名前です。
            </param>
        <param name="endpointName">
            グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したエンドポイント名、型指定されたサブスクリプション、リソース グループとプロファイルの既存の CDN エンドポイントを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByProfileAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt; ListByProfileAsync (this Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt; ListByProfileAsync(class Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.ListByProfileAsync(Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByProfileAsync : Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.ListByProfileAsync (operations, resourceGroupName, profileName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions/&lt;ListByProfileAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="profileName">
            リソース グループ内で一意である CDN プロファイルの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            既存の CDN エンドポイントを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByProfileNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt; ListByProfileNextAsync (this Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt; ListByProfileNextAsync(class Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.ListByProfileNextAsync(Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByProfileNextAsync : Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.ListByProfileNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions/&lt;ListByProfileNextAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations" RefType="this" />
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
            既存の CDN エンドポイントを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListResourceUsageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt; ListResourceUsageAsync (this Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt; ListResourceUsageAsync(class Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.ListResourceUsageAsync(Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListResourceUsageAsync : Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.ListResourceUsageAsync (operations, resourceGroupName, profileName, endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions/&lt;ListResourceUsageAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="profileName">
            リソース グループ内で一意である CDN プロファイルの名前です。
            </param>
        <param name="endpointName">
            グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            クォータと地理的フィルターおよび特定のエンドポイントでカスタム ドメインの使用状況を確認します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListResourceUsageNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt; ListResourceUsageNextAsync (this Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt; ListResourceUsageNextAsync(class Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.ListResourceUsageNextAsync(Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListResourceUsageNextAsync : Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.ListResourceUsageNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions/&lt;ListResourceUsageNextAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations" RefType="this" />
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
            クォータと地理的フィルターおよび特定のエンドポイントでカスタム ドメインの使用状況を確認します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task LoadContentAsync (this Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, System.Collections.Generic.IList&lt;string&gt; contentPaths, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task LoadContentAsync(class Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, class System.Collections.Generic.IList`1&lt;string&gt; contentPaths, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.LoadContentAsync(Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations,System.String,System.String,System.String,System.Collections.Generic.IList{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member LoadContentAsync : Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations * string * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.LoadContentAsync (operations, resourceGroupName, profileName, endpointName, contentPaths, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions/&lt;LoadContentAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="contentPaths" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="profileName">
            リソース グループ内で一意である CDN プロファイルの名前です。
            </param>
        <param name="endpointName">
            グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。
            </param>
        <param name="contentPaths">
            読み込まれるコンテンツへのパス。 パスは、元のファイルの相対 URL を指定します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            CDN のコンテンツを事前に読み込みます。 Verizon プロファイルで使用できます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PurgeContentAsync (this Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, System.Collections.Generic.IList&lt;string&gt; contentPaths, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PurgeContentAsync(class Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, class System.Collections.Generic.IList`1&lt;string&gt; contentPaths, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.PurgeContentAsync(Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations,System.String,System.String,System.String,System.Collections.Generic.IList{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PurgeContentAsync : Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations * string * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.PurgeContentAsync (operations, resourceGroupName, profileName, endpointName, contentPaths, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions/&lt;PurgeContentAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="contentPaths" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="profileName">
            リソース グループ内で一意である CDN プロファイルの名前です。
            </param>
        <param name="endpointName">
            グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。
            </param>
        <param name="contentPaths">
            消去するコンテンツへのパス。 ファイル パスまたはワイルド カード ディレクトリを記述できます。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            CDN からコンテンツを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt; StartAsync (this Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt; StartAsync(class Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.StartAsync(Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StartAsync : Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.StartAsync (operations, resourceGroupName, profileName, endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions/&lt;StartAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="profileName">
            リソース グループ内で一意である CDN プロファイルの名前です。
            </param>
        <param name="endpointName">
            グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            停止状態にある既存の CDN エンドポイントを開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt; StopAsync (this Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt; StopAsync(class Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.StopAsync(Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StopAsync : Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.StopAsync (operations, resourceGroupName, profileName, endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions/&lt;StopAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="profileName">
            リソース グループ内で一意である CDN プロファイルの名前です。
            </param>
        <param name="endpointName">
            グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            既存の実行中の CDN エンドポイントを停止します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt; UpdateAsync (this Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner endpointUpdateProperties, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt; UpdateAsync(class Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, class Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner endpointUpdateProperties, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations * string * string * string * Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.UpdateAsync (operations, resourceGroupName, profileName, endpointName, endpointUpdateProperties, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="endpointUpdateProperties" Type="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="profileName">
            リソース グループ内で一意である CDN プロファイルの名前です。
            </param>
        <param name="endpointName">
            グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。
            </param>
        <param name="endpointUpdateProperties">
            エンドポイントの更新のプロパティ
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したエンドポイント名、型指定されたサブスクリプション、リソース グループとプロファイルでは、既存の CDN エンドポイントを更新します。 エンドポイントの作成後は、タグと配信元ホスト ヘッダーのみを更新できます。 元のドメインを更新するには、Origin の更新操作を使用します。 カスタム ドメインを更新するには、カスタム ドメインの更新操作を使用します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateCustomDomainAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ValidateCustomDomainOutputInner&gt; ValidateCustomDomainAsync (this Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, string hostName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.ValidateCustomDomainOutputInner&gt; ValidateCustomDomainAsync(class Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, string hostName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.ValidateCustomDomainAsync(Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ValidateCustomDomainAsync : Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ValidateCustomDomainOutputInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions.ValidateCustomDomainAsync (operations, resourceGroupName, profileName, endpointName, hostName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.EndpointsOperationsExtensions/&lt;ValidateCustomDomainAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ValidateCustomDomainOutputInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="profileName">
            リソース グループ内で一意である CDN プロファイルの名前です。
            </param>
        <param name="endpointName">
            グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。
            </param>
        <param name="hostName">
            カスタム ドメインのホスト名。 ドメイン名である必要があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            DNS の適切な CDN エンドポイントにマッピングされていることを確認するカスタム ドメインのマッピングを検証します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>