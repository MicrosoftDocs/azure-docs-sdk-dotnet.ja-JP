<Type Name="FunctionsOperationsExtensions" FullName="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class FunctionsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit FunctionsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module FunctionsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type FunctionsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            FunctionsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginTest">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus BeginTest (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, Microsoft.Azure.Management.StreamAnalytics.Models.Function function = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus BeginTest(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, class Microsoft.Azure.Management.StreamAnalytics.Models.Function function) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.BeginTest(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Function)" />
      <MemberSignature Language="F#" Value="static member BeginTest : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Function -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.BeginTest (operations, resourceGroupName, jobName, functionName, function)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="functionName">
            関数の名前。
            </param>
        <param name="function">
            指定された関数が既に存在しない場合、このパラメーターは、テストするためのもので、フル機能定義を含める必要があります。 既に指定された関数が存在する場合は、この省略可能ですが、または指定した場合、既存の関数をテストする場合は null、(PATCH 操作) とまったく同じ既存の関数に対応するプロパティを指定したプロパティが上書きされますおよび結果として得られる関数がテストされます。
            </param>
        <summary>
            関数の提供情報が有効かどうか。 関数の背後にある、基になる web サービスへの接続をテストまたは指定された関数のコードの構文が正しいことを確認してから範囲で指定できます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginTestAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; BeginTestAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, Microsoft.Azure.Management.StreamAnalytics.Models.Function function = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; BeginTestAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, class Microsoft.Azure.Management.StreamAnalytics.Models.Function function, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.BeginTestAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Function,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginTestAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Function * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.BeginTestAsync (operations, resourceGroupName, jobName, functionName, function, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;BeginTestAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="functionName">
            関数の名前。
            </param>
        <param name="function">
            指定された関数が既に存在しない場合、このパラメーターは、テストするためのもので、フル機能定義を含める必要があります。 既に指定された関数が存在する場合は、この省略可能ですが、または指定した場合、既存の関数をテストする場合は null、(PATCH 操作) とまったく同じ既存の関数に対応するプロパティを指定したプロパティが上書きされますおよび結果として得られる関数がテストされます。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            関数の提供情報が有効かどうか。 関数の背後にある、基になる web サービスへの接続をテストまたは指定された関数のコードの構文が正しいことを確認してから範囲で指定できます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplace">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Function CreateOrReplace (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Function CreateOrReplace(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.CreateOrReplace(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Function,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member CreateOrReplace : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Function * string * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Function" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.CreateOrReplace (operations, function, resourceGroupName, jobName, functionName, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Function</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="function">
            新しい関数を作成するか、ストリーミング ジョブの下にある既存のものを置き換えるに使用される関数の定義。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="functionName">
            関数の名前。
            </param>
        <param name="ifMatch">
            関数の ETag です。 常に現在の関数を上書きするには、この値を省略します。 誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。
            </param>
        <param name="ifNoneMatch">
            設定 ' *' を作成する新しい関数を既存の関数の更新を防ぐために使用できるようにします。 その他の値は、412 の前提条件が失敗の応答になります。
            </param>
        <summary>
            関数を作成するか、既存のストリーミング ジョブの下で既に既存の関数を置き換えます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; CreateOrReplaceAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; CreateOrReplaceAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.CreateOrReplaceAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Function,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrReplaceAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Function * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.CreateOrReplaceAsync (operations, function, resourceGroupName, jobName, functionName, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;CreateOrReplaceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="function">
            新しい関数を作成するか、ストリーミング ジョブの下にある既存のものを置き換えるに使用される関数の定義。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="functionName">
            関数の名前。
            </param>
        <param name="ifMatch">
            関数の ETag です。 常に現在の関数を上書きするには、この値を省略します。 誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。
            </param>
        <param name="ifNoneMatch">
            設定 ' *' を作成する新しい関数を既存の関数の更新を防ぐために使用できるようにします。 その他の値は、412 の前提条件が失敗の応答になります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            関数を作成するか、既存のストリーミング ジョブの下で既に既存の関数を置き換えます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.Delete(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IFunctionsOperations, resourceGroupName As String, jobName As String, functionName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.Delete (operations, resourceGroupName, jobName, functionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="functionName">
            関数の名前。
            </param>
        <summary>
            ストリーミング ジョブから関数を削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.DeleteAsync (operations, resourceGroupName, jobName, functionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="functionName">
            関数の名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ストリーミング ジョブから関数を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Function Get (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Function Get(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.Get(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IFunctionsOperations, resourceGroupName As String, jobName As String, functionName As String) As Function" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Function" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.Get (operations, resourceGroupName, jobName, functionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Function</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="functionName">
            関数の名前。
            </param>
        <summary>
            指定された関数の詳細を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; GetAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; GetAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.GetAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.GetAsync (operations, resourceGroupName, jobName, functionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="functionName">
            関数の名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された関数の詳細を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; ListByStreamingJob (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string select = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; ListByStreamingJob(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string select) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.ListByStreamingJob(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByStreamingJob (operations As IFunctionsOperations, resourceGroupName As String, jobName As String, Optional select As String = null) As IPage(Of Function)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJob : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.ListByStreamingJob (operations, resourceGroupName, jobName, select)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="select" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="select">
            $Select OData クエリ パラメーター。 これは、応答に含める構造型プロパティのコンマ区切りの一覧または"*"すべてのプロパティを含めます。既定では、診断を除くすべてのプロパティが返されます。現在のみを受け入れる '*' 有効な値として。
            </param>
        <summary>
            すべての指定したストリーミング ジョブの下で関数の一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt; ListByStreamingJobAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string select = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt; ListByStreamingJobAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string select, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.ListByStreamingJobAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJobAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.ListByStreamingJobAsync (operations, resourceGroupName, jobName, select, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;ListByStreamingJobAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="select">
            $Select OData クエリ パラメーター。 これは、応答に含める構造型プロパティのコンマ区切りの一覧または"*"すべてのプロパティを含めます。既定では、診断を除くすべてのプロパティが返されます。現在のみを受け入れる '*' 有効な値として。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            すべての指定したストリーミング ジョブの下で関数の一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; ListByStreamingJobNext (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; ListByStreamingJobNext(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.ListByStreamingJobNext(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByStreamingJobNext (operations As IFunctionsOperations, nextPageLink As String) As IPage(Of Function)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJobNext : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.ListByStreamingJobNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
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
            すべての指定したストリーミング ジョブの下で関数の一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt; ListByStreamingJobNextAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt; ListByStreamingJobNextAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.ListByStreamingJobNextAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJobNextAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.ListByStreamingJobNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;ListByStreamingJobNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
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
            すべての指定したストリーミング ジョブの下で関数の一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrieveDefaultDefinition">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Function RetrieveDefaultDefinition (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters functionRetrieveDefaultDefinitionParameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Function RetrieveDefaultDefinition(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, class Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters functionRetrieveDefaultDefinitionParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.RetrieveDefaultDefinition(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters)" />
      <MemberSignature Language="F#" Value="static member RetrieveDefaultDefinition : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Function" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.RetrieveDefaultDefinition (operations, resourceGroupName, jobName, functionName, functionRetrieveDefaultDefinitionParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Function</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="functionRetrieveDefaultDefinitionParameters" Type="Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="functionName">
            関数の名前。
            </param>
        <param name="functionRetrieveDefaultDefinitionParameters">
            パラメーターの既定の定義を取得する関数の種類を指定するために使用します。
            </param>
        <summary>
            指定されたパラメーターに基づいて関数の既定の定義を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrieveDefaultDefinitionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; RetrieveDefaultDefinitionAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters functionRetrieveDefaultDefinitionParameters = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; RetrieveDefaultDefinitionAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, class Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters functionRetrieveDefaultDefinitionParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.RetrieveDefaultDefinitionAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RetrieveDefaultDefinitionAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.RetrieveDefaultDefinitionAsync (operations, resourceGroupName, jobName, functionName, functionRetrieveDefaultDefinitionParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;RetrieveDefaultDefinitionAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="functionRetrieveDefaultDefinitionParameters" Type="Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="functionName">
            関数の名前。
            </param>
        <param name="functionRetrieveDefaultDefinitionParameters">
            パラメーターの既定の定義を取得する関数の種類を指定するために使用します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたパラメーターに基づいて関数の既定の定義を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Test">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus Test (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, Microsoft.Azure.Management.StreamAnalytics.Models.Function function = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus Test(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, class Microsoft.Azure.Management.StreamAnalytics.Models.Function function) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.Test(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Function)" />
      <MemberSignature Language="F#" Value="static member Test : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Function -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.Test (operations, resourceGroupName, jobName, functionName, function)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="functionName">
            関数の名前。
            </param>
        <param name="function">
            指定された関数が既に存在しない場合、このパラメーターは、テストするためのもので、フル機能定義を含める必要があります。 既に指定された関数が存在する場合は、この省略可能ですが、または指定した場合、既存の関数をテストする場合は null、(PATCH 操作) とまったく同じ既存の関数に対応するプロパティを指定したプロパティが上書きされますおよび結果として得られる関数がテストされます。
            </param>
        <summary>
            関数の提供情報が有効かどうか。 関数の背後にある、基になる web サービスへの接続をテストまたは指定された関数のコードの構文が正しいことを確認してから範囲で指定できます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TestAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; TestAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, Microsoft.Azure.Management.StreamAnalytics.Models.Function function = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; TestAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, class Microsoft.Azure.Management.StreamAnalytics.Models.Function function, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.TestAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Function,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member TestAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Function * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.TestAsync (operations, resourceGroupName, jobName, functionName, function, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;TestAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="functionName">
            関数の名前。
            </param>
        <param name="function">
            指定された関数が既に存在しない場合、このパラメーターは、テストするためのもので、フル機能定義を含める必要があります。 既に指定された関数が存在する場合は、この省略可能ですが、または指定した場合、既存の関数をテストする場合は null、(PATCH 操作) とまったく同じ既存の関数に対応するプロパティを指定したプロパティが上書きされますおよび結果として得られる関数がテストされます。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            関数の提供情報が有効かどうか。 関数の背後にある、基になる web サービスへの接続をテストまたは指定された関数のコードの構文が正しいことを確認してから範囲で指定できます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Function Update (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Function Update(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.Update(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Function,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Function * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Function" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.Update (operations, function, resourceGroupName, jobName, functionName, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Function</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="function">
            関数オブジェクトを指定します。 ここで指定されたプロパティ (ie 既存の関数に対応するプロパティが上書きされます。そのプロパティが更新されます)。 ここでは null に設定されている任意のプロパティがありことを意味の既存の関数に対応するプロパティは同じままこの PATCH 操作の結果として変更されません。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="functionName">
            関数の名前。
            </param>
        <param name="ifMatch">
            関数の ETag です。 常に現在の関数を上書きするには、この値を省略します。 誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。
            </param>
        <summary>
            既存のストリーミング ジョブの下にある既存の関数を更新します。 これは、(ie 部分的に更新を使用できます。 1 つまたは 2 つのプロパティの更新)、残りのジョブまたは関数の定義に影響を与えず関数。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; UpdateAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; UpdateAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Function,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Function * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.UpdateAsync (operations, function, resourceGroupName, jobName, functionName, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="function">
            関数オブジェクトを指定します。 ここで指定されたプロパティ (ie 既存の関数に対応するプロパティが上書きされます。そのプロパティが更新されます)。 ここでは null に設定されている任意のプロパティがありことを意味の既存の関数に対応するプロパティは同じままこの PATCH 操作の結果として変更されません。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="functionName">
            関数の名前。
            </param>
        <param name="ifMatch">
            関数の ETag です。 常に現在の関数を上書きするには、この値を省略します。 誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            既存のストリーミング ジョブの下にある既存の関数を更新します。 これは、(ie 部分的に更新を使用できます。 1 つまたは 2 つのプロパティの更新)、残りのジョブまたは関数の定義に影響を与えず関数。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>