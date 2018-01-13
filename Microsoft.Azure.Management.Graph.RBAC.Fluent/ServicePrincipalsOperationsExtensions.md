<Type Name="ServicePrincipalsOperationsExtensions" FullName="Microsoft.Azure.Management.Graph.RBAC.Fluent.ServicePrincipalsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ServicePrincipalsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ServicePrincipalsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Graph.RBAC.Fluent.ServicePrincipalsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ServicePrincipalsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ServicePrincipalsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ServicePrincipalsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner&gt; CreateAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations operations, Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalCreateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner&gt; CreateAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations operations, class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalCreateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.ServicePrincipalsOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations,Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalCreateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations * Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalCreateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.ServicePrincipalsOperationsExtensions.CreateAsync (operations, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.ServicePrincipalsOperationsExtensions/&lt;CreateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalCreateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="parameters">
            サービス プリンシパルを作成するパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ディレクトリ内のサービス プリンシパルを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations operations, string objectId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations operations, string objectId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.ServicePrincipalsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.ServicePrincipalsOperationsExtensions.DeleteAsync (operations, objectId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.ServicePrincipalsOperationsExtensions/&lt;DeleteAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations" RefType="this" />
        <Parameter Name="objectId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="objectId">
            削除するサービス プリンシパルのオブジェクト ID。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ディレクトリからサービス プリンシパルを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner&gt; GetAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations operations, string objectId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner&gt; GetAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations operations, string objectId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.ServicePrincipalsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.ServicePrincipalsOperationsExtensions.GetAsync (operations, objectId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.ServicePrincipalsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations" RefType="this" />
        <Parameter Name="objectId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="objectId">
            取得するサービス プリンシパルのオブジェクト ID。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ディレクトリからサービス プリンシパル情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.ServicePrincipalsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner&gt;&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.ServicePrincipalsOperationsExtensions.ListAsync (operations, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.ServicePrincipalsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            現在のテナントからサービス プリンシパルの一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeyCredentialsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt;&gt; ListKeyCredentialsAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations operations, string objectId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt;&gt; ListKeyCredentialsAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations operations, string objectId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.ServicePrincipalsOperationsExtensions.ListKeyCredentialsAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListKeyCredentialsAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt;&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.ServicePrincipalsOperationsExtensions.ListKeyCredentialsAsync (operations, objectId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.ServicePrincipalsOperationsExtensions/&lt;ListKeyCredentialsAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations" RefType="this" />
        <Parameter Name="objectId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="objectId">
            KeyCredentials を取得する対象のサービス プリンシパルのオブジェクト ID。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したサービス プリンシパルに関連付けられている keyCredentials を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations operations, string nextLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations operations, string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.ServicePrincipalsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner&gt;&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.ServicePrincipalsOperationsExtensions.ListNextAsync (operations, nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.ServicePrincipalsOperationsExtensions/&lt;ListNextAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextLink">
            一覧表示操作の次のリンク。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            現在のテナントからサービス プリンシパルの一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPasswordCredentialsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential&gt;&gt; ListPasswordCredentialsAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations operations, string objectId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential&gt;&gt; ListPasswordCredentialsAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations operations, string objectId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.ServicePrincipalsOperationsExtensions.ListPasswordCredentialsAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListPasswordCredentialsAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential&gt;&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.ServicePrincipalsOperationsExtensions.ListPasswordCredentialsAsync (operations, objectId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.ServicePrincipalsOperationsExtensions/&lt;ListPasswordCredentialsAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations" RefType="this" />
        <Parameter Name="objectId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="objectId">
            サービス プリンシパルのオブジェクト ID。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            サービス プリンシパルに関連付けられている passwordCredentials を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateKeyCredentialsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UpdateKeyCredentialsAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations operations, string objectId, Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredentialsUpdateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UpdateKeyCredentialsAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations operations, string objectId, class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredentialsUpdateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.ServicePrincipalsOperationsExtensions.UpdateKeyCredentialsAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations,System.String,Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredentialsUpdateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateKeyCredentialsAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations * string * Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredentialsUpdateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.ServicePrincipalsOperationsExtensions.UpdateKeyCredentialsAsync (operations, objectId, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.ServicePrincipalsOperationsExtensions/&lt;UpdateKeyCredentialsAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations" RefType="this" />
        <Parameter Name="objectId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredentialsUpdateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="objectId">
            サービス プリンシパル情報を取得する対象のオブジェクト ID。
            </param>
        <param name="parameters">
            既存のサービス プリンシパルの keycredentials を更新するパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            サービス プリンシパルに関連付けられている keycredentials を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatePasswordCredentialsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UpdatePasswordCredentialsAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations operations, string objectId, Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredentialsUpdateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UpdatePasswordCredentialsAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations operations, string objectId, class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredentialsUpdateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.ServicePrincipalsOperationsExtensions.UpdatePasswordCredentialsAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations,System.String,Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredentialsUpdateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdatePasswordCredentialsAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations * string * Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredentialsUpdateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.ServicePrincipalsOperationsExtensions.UpdatePasswordCredentialsAsync (operations, objectId, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.ServicePrincipalsOperationsExtensions/&lt;UpdatePasswordCredentialsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations" RefType="this" />
        <Parameter Name="objectId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredentialsUpdateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="objectId">
            サービス プリンシパルのオブジェクト ID。
            </param>
        <param name="parameters">
            既存のサービス プリンシパルの passwordCredentials を更新するパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            サービス プリンシパルに関連付けられている passwordCredentials を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>