<Type Name="ExitConditions" FullName="Microsoft.Azure.Batch.ExitConditions">
  <TypeSignature Language="C#" Value="public class ExitConditions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExitConditions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ExitConditions" />
  <TypeSignature Language="VB.NET" Value="Public Class ExitConditions" />
  <TypeSignature Language="F#" Value="type ExitConditions = class&#xA;    interface ITransportObjectProvider&lt;ExitConditions&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="365ef-101">バッチ サービスの応答方法、タスクが完了したときにします。</span><span class="sxs-lookup"><span data-stu-id="365ef-101">How the Batch service should respond when a task completes.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExitConditions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ExitConditions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="365ef-102"><see cref="T:Microsoft.Azure.Batch.ExitConditions" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="365ef-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.ExitConditions" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Default">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ExitOptions Default { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.ExitOptions Default" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ExitConditions.Default" />
      <MemberSignature Language="VB.NET" Value="Public Property Default As ExitOptions" />
      <MemberSignature Language="F#" Value="member this.Default : Microsoft.Azure.Batch.ExitOptions with get, set" Usage="Microsoft.Azure.Batch.ExitConditions.Default" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ExitOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="365ef-103">取得またはその他のプロパティのいずれかでカバーされない終了条件によって、タスクが失敗した場合、バッチ サービスの応答方法を設定します。</span><span class="sxs-lookup"><span data-stu-id="365ef-103">Gets or sets how the Batch service should respond if the task fails with an exit condition not covered by any of the other properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="365ef-104">タスクが記載されていない 0 以外の終了コードで終了した場合、この値は使用、<see cref="P:Microsoft.Azure.Batch.ExitConditions.ExitCodes" />または<see cref="P:Microsoft.Azure.Batch.ExitConditions.ExitCodeRanges" />プリプロセス エラーのコレクション場合、<see cref="P:Microsoft.Azure.Batch.ExitConditions.PreProcessingError" />プロパティが、存在しないか、またはファイルを使用してアップロード失敗場合、<see cref="P:Microsoft.Azure.Batch.ExitConditions.FileUploadError" />プロパティは使用されません存在します。</span><span class="sxs-lookup"><span data-stu-id="365ef-104">This value is used if the task exits with any nonzero exit code not listed in the <see cref="P:Microsoft.Azure.Batch.ExitConditions.ExitCodes" /> or <see cref="P:Microsoft.Azure.Batch.ExitConditions.ExitCodeRanges" /> collection, with a preprocessing error if the <see cref="P:Microsoft.Azure.Batch.ExitConditions.PreProcessingError" /> property is not present, or with a file upload failure if the <see cref="P:Microsoft.Azure.Batch.ExitConditions.FileUploadError" /> property is not present.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitCodeRanges">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ExitCodeRangeMapping&gt; ExitCodeRanges { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.ExitCodeRangeMapping&gt; ExitCodeRanges" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ExitConditions.ExitCodeRanges" />
      <MemberSignature Language="VB.NET" Value="Public Property ExitCodeRanges As IList(Of ExitCodeRangeMapping)" />
      <MemberSignature Language="F#" Value="member this.ExitCodeRanges : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ExitCodeRangeMapping&gt; with get, set" Usage="Microsoft.Azure.Batch.ExitConditions.ExitCodeRanges" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ExitCodeRangeMapping&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="365ef-105">取得またはタスクの範囲の終了コードと、バッチ サービスがそれらに応答する方法の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="365ef-105">Gets or sets a list of task exit code ranges and how the Batch service should respond to them.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitCodes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ExitCodeMapping&gt; ExitCodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.ExitCodeMapping&gt; ExitCodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ExitConditions.ExitCodes" />
      <MemberSignature Language="VB.NET" Value="Public Property ExitCodes As IList(Of ExitCodeMapping)" />
      <MemberSignature Language="F#" Value="member this.ExitCodes : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ExitCodeMapping&gt; with get, set" Usage="Microsoft.Azure.Batch.ExitConditions.ExitCodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ExitCodeMapping&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="365ef-106">取得またはタスクの終了コードと、バッチ サービスがそれらに応答する方法の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="365ef-106">Gets or sets a list of task exit codes and how the Batch service should respond to them.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileUploadError">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ExitOptions FileUploadError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.ExitOptions FileUploadError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ExitConditions.FileUploadError" />
      <MemberSignature Language="VB.NET" Value="Public Property FileUploadError As ExitOptions" />
      <MemberSignature Language="F#" Value="member this.FileUploadError : Microsoft.Azure.Batch.ExitOptions with get, set" Usage="Microsoft.Azure.Batch.ExitConditions.FileUploadError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ExitOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="365ef-107">取得またはファイルのアップロード エラーが発生した場合、バッチ サービスの応答方法を設定します。</span><span class="sxs-lookup"><span data-stu-id="365ef-107">Gets or sets how the Batch service should respond if a file upload error occurs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="365ef-108">使用して指定された終了コードで、タスクが終了している<see cref="P:Microsoft.Azure.Batch.ExitConditions.ExitCodes" />または<see cref="P:Microsoft.Azure.Batch.ExitConditions.ExitCodeRanges" />、し、ファイルのアップロード エラーが発生し、終了コードで指定された操作が優先されます。</span><span class="sxs-lookup"><span data-stu-id="365ef-108">If the task exited with an exit code that was specified via <see cref="P:Microsoft.Azure.Batch.ExitConditions.ExitCodes" /> or <see cref="P:Microsoft.Azure.Batch.ExitConditions.ExitCodeRanges" />, and then encountered a file upload error, then the action specified by the exit code takes precedence.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PreProcessingError">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ExitOptions PreProcessingError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.ExitOptions PreProcessingError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ExitConditions.PreProcessingError" />
      <MemberSignature Language="VB.NET" Value="Public Property PreProcessingError As ExitOptions" />
      <MemberSignature Language="F#" Value="member this.PreProcessingError : Microsoft.Azure.Batch.ExitOptions with get, set" Usage="Microsoft.Azure.Batch.ExitConditions.PreProcessingError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ExitOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="365ef-109">取得またはエラーのため開始するタスクが失敗した場合、バッチ サービスの応答方法を設定します。</span><span class="sxs-lookup"><span data-stu-id="365ef-109">Gets or sets how the Batch service should respond if the task fails to start due to an error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>