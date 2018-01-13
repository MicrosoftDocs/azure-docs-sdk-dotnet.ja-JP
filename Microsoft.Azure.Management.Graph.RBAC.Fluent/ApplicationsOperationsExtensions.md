<Type Name="ApplicationsOperationsExtensions" FullName="Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ApplicationsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ApplicationsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ApplicationsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ApplicationsOperationsExtensions = class" />
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
            ApplicationsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt; CreateAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationCreateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt; CreateAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationCreateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations,Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationCreateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations * Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationCreateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.CreateAsync (operations, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions/&lt;CreateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationCreateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="parameters">
            アプリケーションを作成するためのパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            新しいアプリケーションを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, string applicationObjectId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, string applicationObjectId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.DeleteAsync (operations, applicationObjectId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions/&lt;DeleteAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations" RefType="this" />
        <Parameter Name="applicationObjectId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="applicationObjectId">
            アプリケーションのオブジェクト id。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            アプリケーションを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt; GetAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, string applicationObjectId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt; GetAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, string applicationObjectId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.GetAsync (operations, applicationObjectId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations" RefType="this" />
        <Parameter Name="applicationObjectId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="applicationObjectId">
            アプリケーションのオブジェクト id。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            アプリケーション オブジェクト ID によって、アプリケーションを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt;&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.ListAsync (operations, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt;" />
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
            フィルターのパラメーターによって、アプリケーションを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeyCredentialsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt;&gt; ListKeyCredentialsAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, string applicationObjectId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt;&gt; ListKeyCredentialsAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, string applicationObjectId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.ListKeyCredentialsAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListKeyCredentialsAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt;&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.ListKeyCredentialsAsync (operations, applicationObjectId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions/&lt;ListKeyCredentialsAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations" RefType="this" />
        <Parameter Name="applicationObjectId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="applicationObjectId">
            アプリケーションのオブジェクト id。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            アプリケーションに関連付けられている keyCredentials を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, string nextLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt;&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.ListNextAsync (operations, nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions/&lt;ListNextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations" RefType="this" />
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
            現在のテナントからアプリケーションの一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPasswordCredentialsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential&gt;&gt; ListPasswordCredentialsAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, string applicationObjectId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential&gt;&gt; ListPasswordCredentialsAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, string applicationObjectId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.ListPasswordCredentialsAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListPasswordCredentialsAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential&gt;&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.ListPasswordCredentialsAsync (operations, applicationObjectId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions/&lt;ListPasswordCredentialsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations" RefType="this" />
        <Parameter Name="applicationObjectId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="applicationObjectId">
            アプリケーションのオブジェクト id。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            アプリケーションに関連付けられている passwordCredentials を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PatchAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, string applicationObjectId, Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationUpdateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PatchAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, string applicationObjectId, class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationUpdateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.PatchAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations,System.String,Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationUpdateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PatchAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations * string * Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationUpdateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.PatchAsync (operations, applicationObjectId, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions/&lt;PatchAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations" RefType="this" />
        <Parameter Name="applicationObjectId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationUpdateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="applicationObjectId">
            アプリケーションのオブジェクト id。
            </param>
        <param name="parameters">
            アプリケーションを更新する既存のパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            既存のアプリケーションを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateKeyCredentialsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UpdateKeyCredentialsAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, string applicationObjectId, Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredentialsUpdateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UpdateKeyCredentialsAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, string applicationObjectId, class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredentialsUpdateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.UpdateKeyCredentialsAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations,System.String,Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredentialsUpdateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateKeyCredentialsAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations * string * Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredentialsUpdateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.UpdateKeyCredentialsAsync (operations, applicationObjectId, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions/&lt;UpdateKeyCredentialsAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations" RefType="this" />
        <Parameter Name="applicationObjectId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredentialsUpdateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="applicationObjectId">
            アプリケーションのオブジェクト id。
            </param>
        <param name="parameters">
            既存のアプリケーションの keycredentials を更新するパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            アプリケーションに関連付けられている keycredentials を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatePasswordCredentialsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UpdatePasswordCredentialsAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, string applicationObjectId, Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredentialsUpdateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UpdatePasswordCredentialsAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, string applicationObjectId, class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredentialsUpdateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.UpdatePasswordCredentialsAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations,System.String,Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredentialsUpdateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdatePasswordCredentialsAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations * string * Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredentialsUpdateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.UpdatePasswordCredentialsAsync (operations, applicationObjectId, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions/&lt;UpdatePasswordCredentialsAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations" RefType="this" />
        <Parameter Name="applicationObjectId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredentialsUpdateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="applicationObjectId">
            アプリケーションのオブジェクト id。
            </param>
        <param name="parameters">
            既存のアプリケーション passwordCredentials を更新するパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            アプリケーションに関連付けられている passwordCredentials を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>