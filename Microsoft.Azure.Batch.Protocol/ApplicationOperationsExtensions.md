<Type Name="ApplicationOperationsExtensions" FullName="Microsoft.Azure.Batch.Protocol.ApplicationOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ApplicationOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ApplicationOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.ApplicationOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ApplicationOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ApplicationOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ApplicationOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary Get (this Microsoft.Azure.Batch.Protocol.IApplicationOperations operations, string applicationId, Microsoft.Azure.Batch.Protocol.Models.ApplicationGetOptions applicationGetOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary Get(class Microsoft.Azure.Batch.Protocol.IApplicationOperations operations, string applicationId, class Microsoft.Azure.Batch.Protocol.Models.ApplicationGetOptions applicationGetOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ApplicationOperationsExtensions.Get(Microsoft.Azure.Batch.Protocol.IApplicationOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.ApplicationGetOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Batch.Protocol.IApplicationOperations * string * Microsoft.Azure.Batch.Protocol.Models.ApplicationGetOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary" Usage="Microsoft.Azure.Batch.Protocol.ApplicationOperationsExtensions.Get (operations, applicationId, applicationGetOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IApplicationOperations" RefType="this" />
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="applicationGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ApplicationGetOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="applicationId">
            アプリケーションの ID。
            </param>
        <param name="applicationGetOptions">
            操作の追加パラメーター
            </param>
        <summary>
            指定されたアプリケーションに関する情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            この操作は、アプリケーションとコンピューティング ノードで使用可能なバージョンのみを返します。つまり、アプリケーション パッケージの参照で使用できます。 管理者についてアプリケーションとはまだ計算ノードに使用できるバージョンは、Azure ポータルまたは Azure リソース マネージャー API を使用します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt; GetAsync (this Microsoft.Azure.Batch.Protocol.IApplicationOperations operations, string applicationId, Microsoft.Azure.Batch.Protocol.Models.ApplicationGetOptions applicationGetOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt; GetAsync(class Microsoft.Azure.Batch.Protocol.IApplicationOperations operations, string applicationId, class Microsoft.Azure.Batch.Protocol.Models.ApplicationGetOptions applicationGetOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ApplicationOperationsExtensions.GetAsync(Microsoft.Azure.Batch.Protocol.IApplicationOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.ApplicationGetOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Batch.Protocol.IApplicationOperations * string * Microsoft.Azure.Batch.Protocol.Models.ApplicationGetOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;" Usage="Microsoft.Azure.Batch.Protocol.ApplicationOperationsExtensions.GetAsync (operations, applicationId, applicationGetOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.ApplicationOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IApplicationOperations" RefType="this" />
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="applicationGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ApplicationGetOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="applicationId">
            アプリケーションの ID。
            </param>
        <param name="applicationGetOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたアプリケーションに関する情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            この操作は、アプリケーションとコンピューティング ノードで使用可能なバージョンのみを返します。つまり、アプリケーション パッケージの参照で使用できます。 管理者についてアプリケーションとはまだ計算ノードに使用できるバージョンは、Azure ポータルまたは Azure リソース マネージャー API を使用します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt; List (this Microsoft.Azure.Batch.Protocol.IApplicationOperations operations, Microsoft.Azure.Batch.Protocol.Models.ApplicationListOptions applicationListOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt; List(class Microsoft.Azure.Batch.Protocol.IApplicationOperations operations, class Microsoft.Azure.Batch.Protocol.Models.ApplicationListOptions applicationListOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ApplicationOperationsExtensions.List(Microsoft.Azure.Batch.Protocol.IApplicationOperations,Microsoft.Azure.Batch.Protocol.Models.ApplicationListOptions)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Batch.Protocol.IApplicationOperations * Microsoft.Azure.Batch.Protocol.Models.ApplicationListOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;" Usage="Microsoft.Azure.Batch.Protocol.ApplicationOperationsExtensions.List (operations, applicationListOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IApplicationOperations" RefType="this" />
        <Parameter Name="applicationListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ApplicationListOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="applicationListOptions">
            操作の追加パラメーター
            </param>
        <summary>
            すべての指定したアカウントで利用できるアプリケーションの一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            この操作は、アプリケーションとコンピューティング ノードで使用可能なバージョンのみを返します。つまり、アプリケーション パッケージの参照で使用できます。 管理者についてアプリケーションとはまだ計算ノードに使用できるバージョンは、Azure ポータルまたは Azure リソース マネージャー API を使用します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;&gt; ListAsync (this Microsoft.Azure.Batch.Protocol.IApplicationOperations operations, Microsoft.Azure.Batch.Protocol.Models.ApplicationListOptions applicationListOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;&gt; ListAsync(class Microsoft.Azure.Batch.Protocol.IApplicationOperations operations, class Microsoft.Azure.Batch.Protocol.Models.ApplicationListOptions applicationListOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ApplicationOperationsExtensions.ListAsync(Microsoft.Azure.Batch.Protocol.IApplicationOperations,Microsoft.Azure.Batch.Protocol.Models.ApplicationListOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Batch.Protocol.IApplicationOperations * Microsoft.Azure.Batch.Protocol.Models.ApplicationListOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.ApplicationOperationsExtensions.ListAsync (operations, applicationListOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.ApplicationOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IApplicationOperations" RefType="this" />
        <Parameter Name="applicationListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ApplicationListOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="applicationListOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            すべての指定したアカウントで利用できるアプリケーションの一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            この操作は、アプリケーションとコンピューティング ノードで使用可能なバージョンのみを返します。つまり、アプリケーション パッケージの参照で使用できます。 管理者についてアプリケーションとはまだ計算ノードに使用できるバージョンは、Azure ポータルまたは Azure リソース マネージャー API を使用します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt; ListNext (this Microsoft.Azure.Batch.Protocol.IApplicationOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.ApplicationListNextOptions applicationListNextOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt; ListNext(class Microsoft.Azure.Batch.Protocol.IApplicationOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.ApplicationListNextOptions applicationListNextOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ApplicationOperationsExtensions.ListNext(Microsoft.Azure.Batch.Protocol.IApplicationOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.ApplicationListNextOptions)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Batch.Protocol.IApplicationOperations * string * Microsoft.Azure.Batch.Protocol.Models.ApplicationListNextOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;" Usage="Microsoft.Azure.Batch.Protocol.ApplicationOperationsExtensions.ListNext (operations, nextPageLink, applicationListNextOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IApplicationOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="applicationListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ApplicationListNextOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="applicationListNextOptions">
            操作の追加パラメーター
            </param>
        <summary>
            すべての指定したアカウントで利用できるアプリケーションの一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            この操作は、アプリケーションとコンピューティング ノードで使用可能なバージョンのみを返します。つまり、アプリケーション パッケージの参照で使用できます。 管理者についてアプリケーションとはまだ計算ノードに使用できるバージョンは、Azure ポータルまたは Azure リソース マネージャー API を使用します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;&gt; ListNextAsync (this Microsoft.Azure.Batch.Protocol.IApplicationOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.ApplicationListNextOptions applicationListNextOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;&gt; ListNextAsync(class Microsoft.Azure.Batch.Protocol.IApplicationOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.ApplicationListNextOptions applicationListNextOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ApplicationOperationsExtensions.ListNextAsync(Microsoft.Azure.Batch.Protocol.IApplicationOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.ApplicationListNextOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Batch.Protocol.IApplicationOperations * string * Microsoft.Azure.Batch.Protocol.Models.ApplicationListNextOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.ApplicationOperationsExtensions.ListNextAsync (operations, nextPageLink, applicationListNextOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.ApplicationOperationsExtensions/&lt;ListNextAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IApplicationOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="applicationListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ApplicationListNextOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="applicationListNextOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            すべての指定したアカウントで利用できるアプリケーションの一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            この操作は、アプリケーションとコンピューティング ノードで使用可能なバージョンのみを返します。つまり、アプリケーション パッケージの参照で使用できます。 管理者についてアプリケーションとはまだ計算ノードに使用できるバージョンは、Azure ポータルまたは Azure リソース マネージャー API を使用します。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>