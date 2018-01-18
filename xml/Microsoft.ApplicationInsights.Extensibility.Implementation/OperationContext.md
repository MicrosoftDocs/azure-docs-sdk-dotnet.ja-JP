<Type Name="OperationContext" FullName="Microsoft.ApplicationInsights.Extensibility.Implementation.OperationContext">
  <TypeSignature Language="C#" Value="public sealed class OperationContext" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit OperationContext extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.Extensibility.Implementation.OperationContext" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class OperationContext" />
  <TypeSignature Language="F#" Value="type OperationContext = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
    <AssemblyVersion>2.3.0.0</AssemblyVersion>
    <AssemblyVersion>2.5.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5d61a-101">操作に関する情報をカプセル化します。</span><span class="sxs-lookup"><span data-stu-id="5d61a-101">Encapsulates information about an operation.</span></span> <span data-ttu-id="5d61a-102">操作は通常、ユーザーの操作から開始するエンド ツー エンド シナリオを反映して (例: ボタンをクリック)。</span><span class="sxs-lookup"><span data-stu-id="5d61a-102">Operation normally reflects an end to end scenario that starts from a user action (e.g. button click).</span></span>  
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CorrelationVector">
      <MemberSignature Language="C#" Value="public string CorrelationVector { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CorrelationVector" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.Implementation.OperationContext.CorrelationVector" />
      <MemberSignature Language="VB.NET" Value="Public Property CorrelationVector As String" />
      <MemberSignature Language="F#" Value="member this.CorrelationVector : string with get, set" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.OperationContext.CorrelationVector" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.EditorBrowsable(System.ComponentModel.EditorBrowsableState.Never)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d61a-103">取得または現在の製品利用統計情報アイテムの相関関係ベクターを設定します。</span><span class="sxs-lookup"><span data-stu-id="5d61a-103">Gets or sets the correlation vector for the current telemetry item.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.Implementation.OperationContext.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.OperationContext.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d61a-104">取得または最上位の操作をアプリケーションで定義された操作 ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="5d61a-104">Gets or sets the application-defined operation ID for the topmost operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.Implementation.OperationContext.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.OperationContext.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d61a-105">取得または設定、アプリケーションで定義された最上位操作の名前。</span><span class="sxs-lookup"><span data-stu-id="5d61a-105">Gets or sets the application-defined topmost operation's name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParentId">
      <MemberSignature Language="C#" Value="public string ParentId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ParentId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.Implementation.OperationContext.ParentId" />
      <MemberSignature Language="VB.NET" Value="Public Property ParentId As String" />
      <MemberSignature Language="F#" Value="member this.ParentId : string with get, set" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.OperationContext.ParentId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d61a-106">取得または設定の親操作 id です。</span><span class="sxs-lookup"><span data-stu-id="5d61a-106">Gets or sets the parent operation ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SyntheticSource">
      <MemberSignature Language="C#" Value="public string SyntheticSource { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SyntheticSource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.Implementation.OperationContext.SyntheticSource" />
      <MemberSignature Language="VB.NET" Value="Public Property SyntheticSource As String" />
      <MemberSignature Language="F#" Value="member this.SyntheticSource : string with get, set" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.OperationContext.SyntheticSource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d61a-107">取得または SyntheticSource アプリケーション定義の操作を設定します。</span><span class="sxs-lookup"><span data-stu-id="5d61a-107">Gets or sets the application-defined operation SyntheticSource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>