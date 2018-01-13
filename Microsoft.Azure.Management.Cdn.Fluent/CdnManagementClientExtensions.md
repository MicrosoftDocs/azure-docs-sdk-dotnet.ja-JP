<Type Name="CdnManagementClientExtensions" FullName="Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClientExtensions">
  <TypeSignature Language="C#" Value="public static class CdnManagementClientExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CdnManagementClientExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClientExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module CdnManagementClientExtensions" />
  <TypeSignature Language="F#" Value="type CdnManagementClientExtensions = class" />
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
            CdnManagementClient の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CheckNameAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CheckNameAvailabilityOutputInner&gt; CheckNameAvailabilityAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient operations, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CheckNameAvailabilityOutputInner&gt; CheckNameAvailabilityAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient operations, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClientExtensions.CheckNameAvailabilityAsync(Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailabilityAsync : Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CheckNameAvailabilityOutputInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClientExtensions.CheckNameAvailabilityAsync (operations, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClientExtensions/&lt;CheckNameAvailabilityAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CheckNameAvailabilityOutputInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient" RefType="this" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="name">
            検証対象のリソース名。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソース名の可用性を確認します。 CDN エンドポイントなど、グローバルに一意な名前のリソースに必要です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOperationsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OperationInner&gt;&gt; ListOperationsAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.OperationInner&gt;&gt; ListOperationsAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClientExtensions.ListOperationsAsync(Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListOperationsAsync : Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OperationInner&gt;&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClientExtensions.ListOperationsAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClientExtensions/&lt;ListOperationsAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OperationInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient" RefType="this" />
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
            すべての利用可能な CDN の REST API 操作の一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOperationsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OperationInner&gt;&gt; ListOperationsNextAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.OperationInner&gt;&gt; ListOperationsNextAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClientExtensions.ListOperationsNextAsync(Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListOperationsNextAsync : Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OperationInner&gt;&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClientExtensions.ListOperationsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClientExtensions/&lt;ListOperationsNextAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OperationInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient" RefType="this" />
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
            すべての利用可能な CDN の REST API 操作の一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListResourceUsageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt; ListResourceUsageAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt; ListResourceUsageAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClientExtensions.ListResourceUsageAsync(Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListResourceUsageAsync : Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClientExtensions.ListResourceUsageAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClientExtensions/&lt;ListResourceUsageAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient" RefType="this" />
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
            クォータと、指定されたサブスクリプションで CDN プロファイルの実際の使用状況を確認してください。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListResourceUsageNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt; ListResourceUsageNextAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt; ListResourceUsageNextAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClientExtensions.ListResourceUsageNextAsync(Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListResourceUsageNextAsync : Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClientExtensions.ListResourceUsageNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CdnManagementClientExtensions/&lt;ListResourceUsageNextAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICdnManagementClient" RefType="this" />
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
            クォータと、指定されたサブスクリプションで CDN プロファイルの実際の使用状況を確認してください。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>