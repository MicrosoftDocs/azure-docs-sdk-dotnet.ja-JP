<Type Name="IDotNetActivity" FullName="Microsoft.Azure.Management.DataFactories.Runtime.IDotNetActivity">
  <TypeSignature Language="C#" Value="public interface IDotNetActivity" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDotNetActivity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Runtime.IDotNetActivity" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDotNetActivity" />
  <TypeSignature Language="F#" Value="type IDotNetActivity = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="deba0-101">アクティビティを実装するために使用します。</span><span class="sxs-lookup"><span data-stu-id="deba0-101">Used to implement an activity.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Execute">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Execute (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedService&gt; linkedServices, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.DataFactories.Models.Dataset&gt; datasets, Microsoft.Azure.Management.DataFactories.Models.Activity activity, Microsoft.Azure.Management.DataFactories.Runtime.IActivityLogger logger);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Execute(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.DataFactories.Models.LinkedService&gt; linkedServices, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.DataFactories.Models.Dataset&gt; datasets, class Microsoft.Azure.Management.DataFactories.Models.Activity activity, class Microsoft.Azure.Management.DataFactories.Runtime.IActivityLogger logger) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Runtime.IDotNetActivity.Execute(System.Collections.Generic.IEnumerable{Microsoft.Azure.Management.DataFactories.Models.LinkedService},System.Collections.Generic.IEnumerable{Microsoft.Azure.Management.DataFactories.Models.Dataset},Microsoft.Azure.Management.DataFactories.Models.Activity,Microsoft.Azure.Management.DataFactories.Runtime.IActivityLogger)" />
      <MemberSignature Language="F#" Value="abstract member Execute : seq&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedService&gt; * seq&lt;Microsoft.Azure.Management.DataFactories.Models.Dataset&gt; * Microsoft.Azure.Management.DataFactories.Models.Activity * Microsoft.Azure.Management.DataFactories.Runtime.IActivityLogger -&gt; System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="iDotNetActivity.Execute (linkedServices, datasets, activity, logger)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="linkedServices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedService&gt;" />
        <Parameter Name="datasets" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.DataFactories.Models.Dataset&gt;" />
        <Parameter Name="activity" Type="Microsoft.Azure.Management.DataFactories.Models.Activity" />
        <Parameter Name="logger" Type="Microsoft.Azure.Management.DataFactories.Runtime.IActivityLogger" />
      </Parameters>
      <Docs>
        <param name="linkedServices"><span data-ttu-id="deba0-102">アクティビティ定義で参照されているリンクされたサービス。</span><span class="sxs-lookup"><span data-stu-id="deba0-102">Linked services referenced by activity definition.</span></span></param>
        <param name="datasets"><span data-ttu-id="deba0-103">アクティビティ定義で参照されるデータセットです。</span><span class="sxs-lookup"><span data-stu-id="deba0-103">Datasets referenced by activity definition.</span></span></param>
        <param name="activity"><span data-ttu-id="deba0-104">アクティビティ定義。</span><span class="sxs-lookup"><span data-stu-id="deba0-104">Activity definition.</span></span></param>
        <param name="logger"><span data-ttu-id="deba0-105">アクティビティの実行中にメッセージを記録するために使用します。</span><span class="sxs-lookup"><span data-stu-id="deba0-105">Used to log messages during activity execution.</span></span></param>
        <summary>
            <span data-ttu-id="deba0-106">アクティビティのインスタンスを実行するには、呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="deba0-106">Called to execute an instance of the activity.</span></span>
            </summary>
        <returns><span data-ttu-id="deba0-107">ダウン ストリーム アクティビティに渡すことのできるプロパティです。</span><span class="sxs-lookup"><span data-stu-id="deba0-107">Properties that may be passed to down-stream activites.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>