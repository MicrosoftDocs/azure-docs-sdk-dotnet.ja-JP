<Type Name="InputsOperationsExtensions" FullName="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class InputsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit InputsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module InputsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type InputsOperationsExtensions = class" />
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
            InputsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginTest">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus BeginTest (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, Microsoft.Azure.Management.StreamAnalytics.Models.Input input = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus BeginTest(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.BeginTest(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Input)" />
      <MemberSignature Language="F#" Value="static member BeginTest : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Input -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.BeginTest (operations, resourceGroupName, jobName, inputName, input)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
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
        <param name="inputName">
            入力の名前。
            </param>
        <param name="input">
            指定された入力が既に存在しない場合、このパラメーターは、テストするためのもので、完全な入力定義を含める必要があります。 既に指定した入力が存在する場合、このパラメーターは省略可能、既存の現状有姿の入力をテストする場合は null またはプロパティが指定されましたが (PATCH 操作) とまったく同じ既存の入力と、その結果で対応するプロパティを上書き指定した場合入力がテストされます。
            </param>
        <summary>
            入力のデータ ソースが到達可能で、Azure Stream Analytics サービスで使用できるかどうかをテストします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginTestAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; BeginTestAsync (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, Microsoft.Azure.Management.StreamAnalytics.Models.Input input = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; BeginTestAsync(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.BeginTestAsync(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Input,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginTestAsync : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Input * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.BeginTestAsync (operations, resourceGroupName, jobName, inputName, input, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions/&lt;BeginTestAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
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
        <param name="inputName">
            入力の名前。
            </param>
        <param name="input">
            指定された入力が既に存在しない場合、このパラメーターは、テストするためのもので、完全な入力定義を含める必要があります。 既に指定した入力が存在する場合、このパラメーターは省略可能、既存の現状有姿の入力をテストする場合は null またはプロパティが指定されましたが (PATCH 操作) とまったく同じ既存の入力と、その結果で対応するプロパティを上書き指定した場合入力がテストされます。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            入力のデータ ソースが到達可能で、Azure Stream Analytics サービスで使用できるかどうかをテストします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplace">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Input CreateOrReplace (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Input CreateOrReplace(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.CreateOrReplace(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Input,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member CreateOrReplace : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Input * string * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Input" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.CreateOrReplace (operations, input, resourceGroupName, jobName, inputName, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Input</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="input">
            新しい入力を作成するか、ストリーミング ジョブの下にある既存のものを置き換えるに使用される入力の定義。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="inputName">
            入力の名前。
            </param>
        <param name="ifMatch">
            入力の ETag です。 常に現在の入力を上書きするには、この値を省略します。 誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。
            </param>
        <param name="ifNoneMatch">
            設定 ' *' を作成するが、既存の入力の更新を防ぐために、新しい入力を許可します。 その他の値は、412 の前提条件が失敗の応答になります。
            </param>
        <summary>
            入力を作成するか、既存のストリーミング ジョブの下で、既に既存の入力を置き換えます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; CreateOrReplaceAsync (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; CreateOrReplaceAsync(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.CreateOrReplaceAsync(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Input,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrReplaceAsync : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Input * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.CreateOrReplaceAsync (operations, input, resourceGroupName, jobName, inputName, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions/&lt;CreateOrReplaceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="input">
            新しい入力を作成するか、ストリーミング ジョブの下にある既存のものを置き換えるに使用される入力の定義。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="inputName">
            入力の名前。
            </param>
        <param name="ifMatch">
            入力の ETag です。 常に現在の入力を上書きするには、この値を省略します。 誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。
            </param>
        <param name="ifNoneMatch">
            設定 ' *' を作成するが、既存の入力の更新を防ぐために、新しい入力を許可します。 その他の値は、412 の前提条件が失敗の応答になります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            入力を作成するか、既存のストリーミング ジョブの下で、既に既存の入力を置き換えます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.Delete(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IInputsOperations, resourceGroupName As String, jobName As String, inputName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.Delete (operations, resourceGroupName, jobName, inputName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
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
        <param name="inputName">
            入力の名前。
            </param>
        <summary>
            ストリーミング ジョブから入力を削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.DeleteAsync (operations, resourceGroupName, jobName, inputName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
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
        <param name="inputName">
            入力の名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ストリーミング ジョブから入力を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Input Get (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Input Get(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.Get(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IInputsOperations, resourceGroupName As String, jobName As String, inputName As String) As Input" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Input" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.Get (operations, resourceGroupName, jobName, inputName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Input</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
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
        <param name="inputName">
            入力の名前。
            </param>
        <summary>
            詳細については、指定された入力を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; GetAsync (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; GetAsync(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.GetAsync(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.GetAsync (operations, resourceGroupName, jobName, inputName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
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
        <param name="inputName">
            入力の名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            詳細については、指定された入力を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; ListByStreamingJob (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string select = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; ListByStreamingJob(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string select) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.ListByStreamingJob(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByStreamingJob (operations As IInputsOperations, resourceGroupName As String, jobName As String, Optional select As String = null) As IPage(Of Input)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJob : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.ListByStreamingJob (operations, resourceGroupName, jobName, select)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
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
            すべての指定したストリーミング ジョブの下にある入力の一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt; ListByStreamingJobAsync (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string select = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt; ListByStreamingJobAsync(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string select, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.ListByStreamingJobAsync(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJobAsync : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.ListByStreamingJobAsync (operations, resourceGroupName, jobName, select, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions/&lt;ListByStreamingJobAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
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
            すべての指定したストリーミング ジョブの下にある入力の一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; ListByStreamingJobNext (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; ListByStreamingJobNext(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.ListByStreamingJobNext(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByStreamingJobNext (operations As IInputsOperations, nextPageLink As String) As IPage(Of Input)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJobNext : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.ListByStreamingJobNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
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
            すべての指定したストリーミング ジョブの下にある入力の一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt; ListByStreamingJobNextAsync (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt; ListByStreamingJobNextAsync(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.ListByStreamingJobNextAsync(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJobNextAsync : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.ListByStreamingJobNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions/&lt;ListByStreamingJobNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
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
            すべての指定したストリーミング ジョブの下にある入力の一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Test">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus Test (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, Microsoft.Azure.Management.StreamAnalytics.Models.Input input = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus Test(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.Test(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Input)" />
      <MemberSignature Language="F#" Value="static member Test : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Input -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.Test (operations, resourceGroupName, jobName, inputName, input)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
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
        <param name="inputName">
            入力の名前。
            </param>
        <param name="input">
            指定された入力が既に存在しない場合、このパラメーターは、テストするためのもので、完全な入力定義を含める必要があります。 既に指定した入力が存在する場合、このパラメーターは省略可能、既存の現状有姿の入力をテストする場合は null またはプロパティが指定されましたが (PATCH 操作) とまったく同じ既存の入力と、その結果で対応するプロパティを上書き指定した場合入力がテストされます。
            </param>
        <summary>
            入力のデータ ソースが到達可能で、Azure Stream Analytics サービスで使用できるかどうかをテストします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TestAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; TestAsync (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, Microsoft.Azure.Management.StreamAnalytics.Models.Input input = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; TestAsync(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.TestAsync(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Input,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member TestAsync : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Input * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.TestAsync (operations, resourceGroupName, jobName, inputName, input, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions/&lt;TestAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
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
        <param name="inputName">
            入力の名前。
            </param>
        <param name="input">
            指定された入力が既に存在しない場合、このパラメーターは、テストするためのもので、完全な入力定義を含める必要があります。 既に指定した入力が存在する場合、このパラメーターは省略可能、既存の現状有姿の入力をテストする場合は null またはプロパティが指定されましたが (PATCH 操作) とまったく同じ既存の入力と、その結果で対応するプロパティを上書き指定した場合入力がテストされます。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            入力のデータ ソースが到達可能で、Azure Stream Analytics サービスで使用できるかどうかをテストします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Input Update (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Input Update(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.Update(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Input,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Input * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Input" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.Update (operations, input, resourceGroupName, jobName, inputName, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Input</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="input">
            入力オブジェクトです。 ここで指定されたプロパティ (ie 既存の入力の対応するプロパティが上書きされます。そのプロパティが更新されます)。 ここでは null に設定されている任意のプロパティがありことを意味既存の入力の対応するプロパティは同じままこの PATCH 操作の結果として変更されません。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="inputName">
            入力の名前。
            </param>
        <param name="ifMatch">
            入力の ETag です。 常に現在の入力を上書きするには、この値を省略します。 誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。
            </param>
        <summary>
            既存のストリーミング ジョブの下で、既存の入力を更新します。 これは、(ie 部分的に更新を使用できます。 1 つまたは 2 つのプロパティの更新)、残りのジョブまたは入力の定義に影響を与えずに入力します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; UpdateAsync (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; UpdateAsync(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Input,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Input * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.UpdateAsync (operations, input, resourceGroupName, jobName, inputName, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="input">
            入力オブジェクトです。 ここで指定されたプロパティ (ie 既存の入力の対応するプロパティが上書きされます。そのプロパティが更新されます)。 ここでは null に設定されている任意のプロパティがありことを意味既存の入力の対応するプロパティは同じままこの PATCH 操作の結果として変更されません。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="inputName">
            入力の名前。
            </param>
        <param name="ifMatch">
            入力の ETag です。 常に現在の入力を上書きするには、この値を省略します。 誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            既存のストリーミング ジョブの下で、既存の入力を更新します。 これは、(ie 部分的に更新を使用できます。 1 つまたは 2 つのプロパティの更新)、残りのジョブまたは入力の定義に影響を与えずに入力します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>